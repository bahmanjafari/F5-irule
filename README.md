# F5-irule
F5 irule 

#### F5_Log_All_Req_AND_PostBody_to_Splunk: 
Log all requests contain get and post plus postbody and respone
thanks "@sebbycorp"

#### Prevent_XFF_Header_And_Insert_X_REAL_IP
Remove X-Forwarded-For to prevent XFF spoofing and Add XFF and X_Real_IP based on source IP 

#### Select_Pool_BasedOn_Src_IP:
select pool based on source IP address and limit access

#### Redirect_Specific_HTTPHost_To_HTTPS
By doing it this way we can use whats called an "iRule Data Group List" to contain all the domains we want to redirect.<br />
Each time we want to add a domain we don't need to touch the iRule itself, only add the domain to the data group list.<br />
