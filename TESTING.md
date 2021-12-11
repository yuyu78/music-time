# TESTING Music TIme

[README file](https://github.com/yuyu78/music-time/blob/main/README.md)   

## Table of contents
1. [Devices tested](#device-tested)   

2. [Browsers tested](#browsers-tested)   

3. [Testing User Stories](#testing-user-stories)  

4. [Manual Testing](#manual-testing)  

5. [Bugs](#bugs)  

6. [Validators](#validators)

7. [Lighthouse Testing](#lighthouse-testing)

## Devices tested <a name="device-tested"></a>

## Browsers tested <a name="browsers-tested"></a>

## Testing User Stories <a name="testing-user-stories"></a>

## Manual Testing <a name="manual-testing"></a>

## Bugs <a name="bugs"></a>

* On Ipad pro, the footer was not placed on the bottom so there was a space under:   
![space-footer](https://user-images.githubusercontent.com/76018052/143784078-941acc8c-0c95-46b3-bcb2-4332a492677b.PNG)    
To remove this space on the device Ipad Pro, I found the solution [here](https://bbpress.org/forums/topic/footer-on-ipad-has-whitespace-below-how-do-i-remove/).  
I just had to set a minimum height and adjust to make responsive  on Ipad  
![margin-tb](https://user-images.githubusercontent.com/76018052/145436139-a57929bc-b5d1-4ebb-84af-92759b64e59b.PNG)  

* After exporting the API keys, when I refreshed the page, and error message came up  
![authentification error](https://user-images.githubusercontent.com/76018052/145440999-163650e8-82e6-4325-9a5f-904e22b6825c.PNG)  
I found the solution in Slack community: a tutor advised when we export the API keys from the terminal, we have to run the runserver command in the same terminal in order for Django to able to access them.

* I tried to make migrations for my models btu when I put in the command "python3 manage.py migrate --plan", it showed a message there is no planned migrations operations.  
![no migration](https://user-images.githubusercontent.com/76018052/145674967-98855c94-1093-407b-b0fb-fcbbf6124ff6.PNG)  
I found the solution in slack community: it is because I have only done a dry run, but I need to run the makemigrations without the --dry-run option, so I followed the step bellow in the command to successfully migrate the change:  
> python3 manage.py makemigrations --dry-run  
> python3 manage.py makemigrations   
> python3 manage.py migrate --plan  
> python3 manage.py migrate  


## Validators <a name="validators"></a>

## Lighthouse testing <a name="lighthouse-testing"></a>  