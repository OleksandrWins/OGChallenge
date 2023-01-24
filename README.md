Hello world!
As a switcher, software development is a breath of fresh air for me, but also I wanted to try testing.
So, development and testing seem perfectly synergetic! :)

TASK 2: selectors

Subtask 1:

\panel_heading_xpath\
\//*[@id="__next"]/form/div/div[1]/h5\
//*[text()="Scouts Panel"]
//h | //child::div/h5

login_xpath
//*[@id="login"]
//*[@name='login']
//*[contains(@name, "login")]

password_xpath
//*[@id="password"]
//*[@name='password']
//*[contains(@name, "pass")]

remind_password_xpath
//*[@id="__next"]/form/div/div[1]/a
//*[text()="Remind password"]
//child::div/a

language_button_xpath
//*[@id="menu-"]/div[3]/ul/li[1]
//*[@role="button"]
//*[text()="English" | text()="Polski"]

sign_in_button_xpath
//*[@id="__next"]/form/div/div[2]/button/span[1]
//*[text()="Sign in"]
//child::button/span[2]

