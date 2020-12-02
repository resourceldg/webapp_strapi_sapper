# webapp_strapi_sapper

## Requirements!

### Customers Requirements

1 scan offers with qr code
2 get and share offers with offer code (mode anonimus)
3 get and share offers whit link code (mode anonimus)
4 register process
5 login process
                |
                |
                |_ IN PROFILE (Costumer Logged)
                  5.0 view points (just segment 0-10000 step 100 if it reaches limit reload and add one star reputation)
                  5.1 view stars reputations ()
                  5.2 view offers on
                  5.3 view offers off (maybe change to "on" with make counter offer)
                  5.4 view net offers on
                  5.5 view net offers off (maybe change to "on" with make counter offer)
                  5.6 view membership level (this atribute is related with stars reputations)
                  5.7 view banner spot 
                  5.8 Share offer (banner spot) buttom
                  5.9 scan qr code
                  5.10 to register purchase code
                  5.11 view customer code
                  5.12 get and share offers with offer code (mode logged)
                  5.13 get and share offers whit link code (mode logged)
                |
                |
                |_ IN PROFILE/SETTINGS (Costumer Logged)
                  6.0 update username, email, phone, street, street number, postcode, cover (avatar)
                  6.1 logout process
 
### Sellers Requirements

login process
                |
                |
                |_ IN PROFILE (Seller Logged)
                             | 
                             |_ INACTIVE (no match with shop)
                             
                                        0.0 see points (just segment 0-10000 step 100 if it reaches limit reload and add one star reputation)
                                        0.1 see goals reputations ()
                                        0.2 see seller code
                                        0.3 share offers on
                                        0.4 share offers off (maybe change to "on" with make counter offer)
                                        0.5 share net offers on
                                        0.6 share net offers off (maybe change to "on" with make counter offer)
                                        0.7 see membership level (this atribute is related with goals reputations)
                                        0.8 share banner spot
                                       
                                      |
                                      |_ IN PROFILE/SETTINGS (Seller Logged)
                                        6.0 update username, email, phone, street, street number, postcode, cover (avatar)
                                        6.1 share seller profile
                                        6.2 logout process
                                        
                                      |_ PROFILE/PERFORMANCE (Seller Logged)
                                        7.0 view shop performance with time frame
                                        7.1 view all performace with time frame
                                        7.2 share seller profile
                               
                             | 
                             |_ ACTIVE (match at least one shop)
                                       
                                       |_ PROFILE (Seller Logged)
                                       
                                        0.0 see points (just segment 0-10000 step 100 if it reaches limit reload and add one star reputation)
                                        0.1 see goals reputations ()
                                        0.2 view offers on
                                        0.3 share offers off (maybe change to "on" with make counter offer)
                                        0.4 view net offers on
                                        0.5 share net offers off (maybe change to "on" with make counter offer)
                                        0.6 see membership level (this atribute is related with stars reputations)
                                        0.7 view banner spot 
                                        0.8 Share banner spot
                                        0.9 scan qr code or 
                                        0.10 to register purchase code
                                        0.11 see seller code
                                        0.12 get and share offers mode "on", with offer code 
                                        0.13 get and share offers mode "on", whit link code

                                      |
                                      |_ IN PROFILE/SETTINGS (Seller Logged)
                                      
                                        6.0 update username, email, phone, street, street number, postcode, cover (avatar)
                                        6.1 logout process
                                    
                                      
                                      |_ PROFILE/PERFORMANCE (Seller Logged)
                                      
                                        7.0 view shop performance with time frame
                                        7.1 view all performace with time frame
                                        7.2 share seller profile
                                        
### Shop Requirements

login process
                |
                |
                |_ IN PROFILE (Shop Logged)
                             | 
                             |_ INACTIVE ( with shop)
                             
                                        0.0 see points (just segment 0-10000 step 100 if it reaches limit reload and add one star reputation)
                                        0.1 see goals reputations ()
                                        0.2 see seller code
                                        0.3 share offers on
                                        0.4 share offers off (maybe change to "on" with make counter offer)
                                        0.5 share net offers on
                                        0.6 share net offers off (maybe change to "on" with make counter offer)
                                        0.7 see membership level (this atribute is related with goals reputations)
                                        0.8 share banner spot
                                       
                                      |
                                      |_ IN PROFILE/SETTINGS (Seller Logged)
                                        6.0 update username, email, phone, street, street number, postcode, cover (avatar)
                                        6.1 share seller profile
                                        6.2 logout process
                                        
                                      |_ PROFILE/PERFORMANCE (Seller Logged)
                                        7.0 view shop performance with time frame
                                        7.1 view all performace with time frame
                                        7.2 share seller profile
                               
                             | 
                             |_ ACTIVE (match at least one shop)
                                       
                                       |_ PROFILE (Seller Logged)
                                       
                                        0.0 see points (just segment 0-10000 step 100 if it reaches limit reload and add one star reputation)
                                        0.1 see goals reputations ()
                                        0.2 view offers on
                                        0.3 share offers off (maybe change to "on" with make counter offer)
                                        0.4 view net offers on
                                        0.5 share net offers off (maybe change to "on" with make counter offer)
                                        0.6 see membership level (this atribute is related with stars reputations)
                                        0.7 view banner spot 
                                        0.8 Share banner spot
                                        0.9 scan qr code or 
                                        0.10 to register purchase code
                                        0.11 see seller code
                                        0.12 get and share offers mode "on", with offer code 
                                        0.13 get and share offers mode "on", whit link code

                                      |
                                      |_ IN PROFILE/SETTINGS (Seller Logged)
                                      
                                        6.0 update username, email, phone, street, street number, postcode, cover (avatar)
                                        6.1 logout process
                                    
                                      
                                      |_ PROFILE/PERFORMANCE (Seller Logged)
                                      
                                        7.0 view shop performance with time frame
                                        7.1 view all performace with time frame
                                        7.2 share seller profile
                                        
                                        
                                        
