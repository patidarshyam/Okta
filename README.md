# Okta
Third party authentication
------------------------------------------------------------------------------------------------------
#2 OktaSpringBootSAMLDemo app-
*NOTE: in spring Okta SAML configuration example we need to create keystore.jks file in resources/saml/
for creating this-
                    From a terminal window, navigate to the src/main/resources directory of your app and create a saml directory. Navigate into the directory and run the following command. Use “secret” when prompted for a keystore password.
use command- 
                              keytool -genkey -v -keystore keystore.jks -alias spring -keyalg RSA -keysize 2048 -validity 10000
The values for the rest of the questions don’t matter since you’re not generating a real certificate. However, you will need to answer “yes” to the following question.

Is CN=Unknown, OU=Unknown, O=Unknown, L=Unknown, ST=Unknown, C=Unknown correct?
  [no]:
-----------------------------------------------------------------------------------------------------------------                             
                              
