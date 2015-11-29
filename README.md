===========================
== Sign in through Steam ==
===========================
This Plugin for IPS 4.1+ will allow your users to login with their Steam account.

Recommended Installation Requirements:
 - If you are using InvisonPower's Hosted forums, this is already done for you.
* Is curl enabled? If not, install/enable it please.
* Hosting with Free services will not be supported
 - If you are having issues, and use IIS as your web server. Please try switching to Apache or another server type. IIS is known to have random issues.

==========================================================
== INVISION POWER BOARD SUITE 4.1.x SYSTEM REQUIREMENTS ==
==========================================================
 PHP Requirements

    PHP version 5.4.45. Please see advice below
    cURL extension
    Multibyte String extension 
    DOM extension
    GD extension
    MySQLi extension 
    OpenSSL extension
    Session extension
    SimpleXML extension
    XML extension
    XMLReader extension
    XMLWriter extension
    Phar extension
    Zip extension
    512 MB memory limit.

MySQL Requirements

    MySQL version 5.5.46-cll.

Recommendations

None of these items are required in order to continue with the upgrade right now. However, they will be required in a future version of IPS Community Suite. You should make a note of them and contact your hosting provider or system administrator after the upgrade to address them. You can re-run these checks later from the Support section of the Administrator Control Panel.

    You are running PHP version 5.4.45. While this version is compatible, we recommend version 5.5.0 or above.
    You are running MySQL version 5.5.46-cll. While this version is compatible, we recommend version 5.6 or above.


==================
== Installation ==
==================

1. First, upload the contents of the upload folder to your forum root directory.
2. Login to your ACP, and browse to System -> Plugins
3. Click Install New Plugin. Browse to the extracted zip file and upload steam_login.xml
4. Visit - http://steamcommunity.com/dev/apikey and follow the instructions to obtain an API key
5. Navigate to System -> Login Methods, click the edit icon on the Steam row and paste your API key in the API Key input and save
6. Make sure to enable both plugin and login method.
