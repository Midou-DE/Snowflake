# Snowflake


In order to make the connction right be sure that the role you use is associate to your user account by running this command:

    - SHOW GRANTS TO USER <user_account>;

if the role is not in the list you have to added it by:
    - GRANT ROLE <YOUR_ROLE> TO USER <YOUR_USER>;
