# gify-assignment

#h1 This application was designed in order to generate still gif's of the values of the buttons displayed on the page. For example, the ferari button would deploy gif's relating to that string. Also this application was supposed to be able to have the images be clicked, and upon clicking, it would animate the image. This I had quite a lot of trouble with along with other elements I found very difficult in this project.


1. Getting the image buttons to display the proper image.
    * this at first was quite a challenge as I kept trying to store either the value of the entire array, or the last generated string in the array to the queryURL. Also the method in which I solved this issue was by also creating an Id for these buttons upon creation with the stored array value.
2. Getting the images to move upon clicking.
    * This I could not accomplish, although I can see how to do it when the complete api string for each image is broken up and stored into a button, I could not figure out how to store this data state properly so it could be used in an if else function nested into the click function of the image.
3. Creating an input form that allows a user to append new buttons.
    * This step I have yet to achieve and intend to when I follow through with finding my solution for problem two listed above.