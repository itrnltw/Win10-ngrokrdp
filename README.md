# How to make a Win10 RDP with ngrok and github in any device (anything like apple, android and more)
1, Fork this repository by pressing the fork button in the top right screen and clicking "create repository."

2, Go to "ngrok.com" and sign up if your not yet a memeber in the ngrok team

3, Go to settings and press "Secrets and variables", and press create "New repository secret" and name the Secret "NGROK_AUTH_TOKEN", go to ngrok.com again and copy your auth token and paste it on the big box.

4, Go to Actions and click on "All workflows" and select "CI", click on "run workflow", refresh the page and click on build and wait for the "create tunnel" is loading. that means that the "create tunnel" is the timer.

5, Go to "ngrok.com" and click on Cloud Edge and Endpoints and copy the URL Text but not the "tcp://" (example: 0.tcp.ngrok.io:17241)

6, Download "Remote desktop" on the play store and wait for the app to finish, once its done downloading, open the app, press on the "+" Button and "add PC", enter the PC name that you copied in "ngrok.com" URL, and click the arrow looking down and select "Add user account" and enter the username: "runneradmin" and enter the password: "P@ssw0rd!" , turn on admin mode and click on "save", click on the grey box and done.

NOTE: If a box appeared on the screen with a password and a username, please enter: Username: runneradmin
                                                                                    Password: P@ssw0rd!
