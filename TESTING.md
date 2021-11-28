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

* In the product_detail page, there was a space under the footer on tablet and desktop size.  
![footer-space-bottom](https://user-images.githubusercontent.com/76018052/143765459-ecf4e6a1-8d36-48d3-afd6-dc0f26587fbd.PNG)  
To remove this space, I found the solution in [CodeConvey](https://codeconvey.com/footer-at-bottom-of-page-but-not-fixed/).
To do a stick footer at the bottom of the page but not fixed:  
-I had to set the height to 100% for HTML element.  
-Set the position to relative in the body element.  
-Set the position to absolute on tablet and desktop size in the footer element.  

* On Ipad pro, there was a huge unnecessary space under the product detail, which is not good user experience as we need to scroll down to check the footer.  
![space-under-detail](https://user-images.githubusercontent.com/76018052/143766158-50b74b10-44a0-433d-9f3d-6c60f00058ba.PNG)  
To remove this unnecessary spaceon Ipad, I found the solution [here](https://bbpress.org/forums/topic/footer-on-ipad-has-whitespace-below-how-do-i-remove/).  
I just had to set a minimum height on tablet size  
![tablet-size-min-height](https://user-images.githubusercontent.com/76018052/143766238-12799fde-b605-4304-bda6-1c9b4d343a63.PNG)

## Validators <a name="validators"></a>

## Lighthouse testing <a name="lighthouse-testing"></a>  