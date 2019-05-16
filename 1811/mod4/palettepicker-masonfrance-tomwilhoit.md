# Palette Picker Submission Form

 [Project Spec](http://frontend.turing.io/projects/palette-picker.html)

 # Basics

 #### Link to the GitHub Repository for the BE
[palette-picker BE](https://github.com/francepack/palette-picker-api)

 #### Link to the Deployed BE
[heroku BE](https://palette-api-tm.herokuapp.com/)

 #### Link to the GitHub Repository for the FE
[palette-picker FE](https://github.com/TomWilhoit/palette-picker)

 #### Link to the Deployed FE
NA will update if deployed

 ## Completion

 #### Were you able to complete the base functionality?
 I believe we were

 #### Link to an image of your wireframe(s)
[wireframe](https://www.figma.com/file/O8HcYTjKFWQ5ksAA0CtxYYGK/palette-picker?node-id=0%3A1)

 #### Which extensions, if any, did you complete?


 # Code Quality

 #### Link to a specific block of your code on GitHub (from either repository) that you are proud of
[Palette component](https://github.com/TomWilhoit/palette-picker/blob/master/src/Containers/Palette/Palette.js)

 * Why were you proud of this piece of code?  
We like this component because we used object.keys to pull colors from props... that didn't immediately come to us. Also, there is quite a bit of pulling from props here and some creativity was required to get everything in the right place.

 #### Link to a specific block of your code on GitHub that you feel not great about
[sad code](https://github.com/TomWilhoit/palette-picker/blob/master/src/Containers/PalettePicker/PalettePicker.js)

 * Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
We weren't super happy with the chunkyness of this main component, specifically the amount of setting each individual color (color1, color2, etc...) ex- line 39 to 55
Perhaps it is unavoidable, but perhaps we could find a way to make this more clean by using iteration, though once we got it working, we felt that would be something to go back and refactor

 #### Link to Design Inspiration

 * Show us what you used as design inspiration (another color picker site, a dribbble UI element, a user flow, etc.) and explain what you stole from it  
[design inspiration](https://dribbble.com/shots/6486403-Dashboard) 
We were trying to make a 'dashboard' style app like the link above. While we admittedly didn't get as far along with the style as we wanted, we feel we were going down the right path here- doing a dashboard style lead us to make this a single page, no scroll on the body application, while having scrollable boxes within the body for projects and palettes listings   

 #### Reflection on New Concepts

 * Describe your thoughts on server-side testing  
-We found ourselves enjoying that what needed to be tested was pretty clear, although we still had to do some troubleshooting. But with server-side testing, it felt like creating the tests helped us better realize what we were putting into, and getting out, of the server, which helped us write our FE code correctly.

* Describe your thoughts on TravisCI  
- Travis is kinda needy and slow. But it was also nice to be able to see where errors were made, and it ended up streamlining deployment of our BE quite a bit after we did enough troubleshooting to implement TravisCI.

* Describe your thoughts in creating a single project whose codebase was distributed across multiple repositories
- We struggled to link the two, but we found that the organization of everything was nice, as well as the separation. We are starting to not be as intimidated by larger file structures and are more aware of where different informative code may live

#### Please feel free to ask any other questions or make any other statements below!

 Anything else you wanna say!

 We should have gotten our FE deployment and env variable in place sooner. We didn't expect it to be such a challenge. I am not sure if our FE will be deployed by the time of our eval, but we are committed to getting this in place for our own learning benifit even if this is unfulfilled for our eval.
 There was a lot to this project, and unfortunately this fell to the wayside.

 -----


 # Instructor Feedback (Instructor Name)

 ## Specification Adherence

 **x score**: 

 ## User Interface

 **x score**: 

 ## Testing

 **x score**: 

 ## Workflow

 **x score**: 

 # Outcome: pass/fail
