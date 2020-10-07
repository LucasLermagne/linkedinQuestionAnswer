#### What is printed from this code?
vector&lt;int&gt; v(22);
bool b = (v[6]);
printf ("%d", !b);
--
- [ ] Double-click the file
[ ]FALSE
[ ]This code has an error.
[ ]0
[ ]1
-----
What is a class template?
--
It is a class written with the generic programming paradigm, specifying behavior in terms of type parameters rather than specific types.
It is a skeleton source code for a class where the programmer has to fill in specific parts to define the data types and algorithms used.
It is a class that consists only of member variables, with no constructor, destructor, or member functions.
It is a blank superclass intended for inheritance and polymorphism.
-----
Which STL class is the best fit for implementing a collection of data that is always ordered so that the pop operation always gets the greatest of the elements? Suppose you are interested only in push and pop operations.
--
std::list
std::priority_queue
std::vector
std::map
-----
What is this expression equivalent to?
A-&gt;B-&gt;C-&gt;D ------(A->B->C->D)
--
*(*((*A).B).C).D
A.B.C.D
*A.*B.*C.*D
&amp;A.&amp;B.&amp;C.&amp;D ------(&A.&B.&C.&D)
------
What is null in this code?
typedef struct{
    unsigned int  age    : 4;
    unsigned char gender : 1;
    unsigned int  size   : 2;
}child_t;
--
It is a type defined as a structure with bit fields, with 4 bits for age, 1 bit for gender, and 2 bits for size.
It is a type defined as a structure with three unsigned fields initialized as age=4, gender=1, and size=2.
This code causes a compiler error because the colon character is not allowed in struct definitions.
It is a type defined as a structure with three arrays. The size and length of these arrays are age: int[4], gender:char[1], and size:int[2], all unsigned.
-----
Which choice is null a difference between a class and a struct?
--
Template type parameters can be declared with the null keyword, but not with the null keyword.
The default access specifier for members of structs is public, whereas for members of classes, it is private.
Because structs are part of the C programming language, there is some compatibility between C and C++ using structs. This is not the case with classes.
Classes can have member functions; structs cannot.
-------
Which choice shows the contents of vectors pointed by v1 and v2 after running this code?
std::vector &lt;int&gt; *v1 = new std::vector &lt;int&gt; ({1,2,3});
std::vector &lt;int&gt; *v2;
v2=v1;
v1-&gt;push_back(4);
v2-&gt;push_back(5);
--
*v1: {1,2,3,4,5}; *v2: {1,2,3,4,5}
*v1: {1,2,3,4}; *v2: {1,2,3,5}
ERROR
*v1: {1,2,3,4}; *v2: {5}
------
What is an appropriate way of removing null as shown below?
my_class *my_object = new my_class();
--
free(my_object);
delete(my_object);
The garbage collector will destroy the object eventually.
Exiting the scope will destroy the object.
-----
Which operator is overloadable?
?:
.
new
::
-----
You want to sort null, declared below. Which choice is the correct call to null, using a lambda expression as the comparison function?
std::array&lt;uint32_t, 50&gt; my_array;  -----(std::array<uint32_t, 50> my_array;)
--
lambda(uint32_t a, uint32_t b){
              return a &lt; b;   
});

std::sort(my_array.begin(), my_array.end(),lambda);

std::sort(my_array.begin(), my_array.end(), 
          [](uint32_t a, uint32_t b) {
              return a &lt; b;   
          });

lambda(uint32_t a, uint32_t b){
              return a &lt; b;   
});

std::sort(my_array.begin(), my_array.end(),&amp;lambda);

std::sort(my_array.begin(), my_array.end(), 
          lambda(uint32_t a, uint32_t b) {
              return a &lt; b;   
          });
-----
Why does the null receive a function object as one of its parameters?
--
std::sort operates on a template container. The compiler does not know how to relationally compare the values it contains, so a function must be provided to do the comparison.
std::sort will use the parameter function as an error handler. The function will be called if an error occurs.
The std::sort function is a template. The programmer is free to enter the sorting algorithm in a function object as an argument.
Actually, std::sort takes only one argument, which is the container to be sorted.
-----
What would be the output of this code?
int i0=4, i1=6, i2=8;
int&amp; nums[3]={i2,i0,i1};
std::cout&lt;&lt;nums[0]&lt;&lt;nums[1]&lt;&lt;nums[2];
--
The output is the addresses of i2, i0, and i1, in that order, with no spaces.
846
468
There is no output. The code causes a compiler error because nums is an array of references, which is illegal.
-----
You want to have several lines of code that print out some variables for debugging purposes, but you do not want those lines to make it to the final application, for efficiency reasons. Which choice achieves the desired behavior producing the shortest possible code length, regardless of the level of optimization used?
--
// set the following to false for the final application
bool debugging = true;

// copy and customize this for every debugging line
if(debugging){
 cout&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
}
-
// copy and customize this for every debugging line
 cerr&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
-
#define DEBUGGING(x)  #include x 

// copy and customize this for every debugging line

DEBUGGING(
 cout&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
)
-
// comment the following line for the final application
#define DEBUGGING

// copy and customize this for every debugging line
#ifdef DEBUGGING
 cout&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
#endif
------
Which choice is the correct declaration for a class named Dog, derived from the Animal class?
class Animal{
 //...
};
--
class Dog : public Animal{
 //...
};
-
class Dog :: public Animal{
 //...
};
-
public class Dog extends Animal{
 //...
};
-
public class Animal::Dog{
 //...
};
-------
Adobe Photoshop Assessment
---------------------
#### Q1. How can you open a file selected in Lightroom CC for retouching in Photoshop CC? (find all that apply) (Ans 2)
- [ ] Double-click the file
- [x] Choose File > Edit in Photoshop
- [ ] Choose File > Save to Photoshop
- [x] Press Cmd/Ctrl+E


#### Q2. How can you undo one or more changes just made to an image? (find all that apply) (Ans 1)
- [x] Use the keyboard shortcut Cmd/Ctrl+Z
- [ ] Click a state in the history panel
- [ ] Choose File > Undo
- [ ] Press Cmd/Ctrl+U


#### Q3. How can you select a specific layer? (find all that apply) (Ans 2)
- [ ] Click the eye icon in the layers panel
- [x] Use the Move tool with auto-select enabled
- [ ] Right-click the image and select layer
- [x] Press Cmd/Ctrl and click the layer


#### Q4. How can you avoid having transparent edges along the edge of a panoramic photo while retaining the largest image size? (Ans 2)
<img src="https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot%20(441).png?raw=true">
- [ ] Choose the Cylindrical method
- [ ] Choose the Perspective method.
- [ ] Adjust the Boundary Warp slider.
- [x] Select Auto Crop. //https://helpx.adobe.com/photoshop/using/selecting-grouping-linking-layers.html

#### Q5. How do you crop a document without permanently discarding pixels along the edge? (Ans 3)
- [ ] Clear the Delete Cropped Pixels box.
- [ ] Select the Delete Cropped Pixels box.
- [x] Use the Smart Crop tool.
- [ ] Hold the Alt (Windows) or Option (Mac) key.


#### Q6. What feature should you use to simulate the in-camera development recipes applied by manufacturers with your own raw files? (Ans 2)
- [ ] presets
- [x] Camera Matching profiles
- [ ] calibration
- [ ] snapshots


#### Q7. When working in an RGB document, which option is NOT a method for the Select Color Range command? 
- [ ] Sampled Colors
- [ ] Skin Tones
- [ ] Key (Blacks)
- [ ] Out of Gamut


#### Q8. How do you access the Auto Color Correction Options dialog box? (Ans 2)
- [ ] Select Image > Auto Tone.
- [x] Select Image > Auto Color.
- [ ] Alt-click (Option-click) the Auto button in the Properties panel when you have a Levels or Curves adjustment layer targeted in the Layers panel.
- [ ] Hold down the Alt (Option) key and select Image > Auto Color.


#### Q9. Which options are available when using the Free Transform command on a Smart Object? (Select all that apply.) 
A. Content-Aware Scale
B. Scale
C. Warp
D. Distort
E. Perspective Warp

- [x] C,D
- [ ] D,E
- [x] B,C
- [ ] C,E


#### Q10. What is considered the minimum DPI for photographic-quality inkjet printing?
- [x] 300
- [ ] 100
- [ ] 1,000
- [ ] 72

#### Q11. Which scanner type is capable of producing the highest resolution scans? (Ans 1)
- [x] flatbed scanner
- [ ] slide scanner
- [ ] all-in-one unit
- [ ] drum scanner


#### Q12. Which format does NOT support an alpha channel? (Ans 2)
- [ ] PSD
- [x] PNG
- [ ] TIFF
- [ ] BMP


#### Q13. What is the best way to save multiple images into a single PDF? (Ans 3)
- [ ] Save each PDF separately first and then combine them.
- [ ] Check to see if you have Acrobat Professional installed.
- [x] Use the PDF Presentation command.
- [ ] Click File > Export > Export Layers to Files.


#### Q14. What option cannot be adjusted with the Print command directly in the Print window? (Ans 3)
- [ ] size of the image
- [ ] position on the page.
- [x] paper quality.
- [ ] color management policies


#### Q15. Which statement best describes the Quick Mask feature? (Ans 2)
- [ ] It allows you to use the Pen tool to edit a selection
- [x] It allows you to use the Brush tool to create or refine a selection
- [ ] It allows you to duplicate a mask quickly.
- [ ] It allows you to convert a vector mask to a layer mask.


#### Q16. What Photoshop feature was used to convert this image to black and white? (Ans 3)
<img src="https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot%20(444).png?raw=true">
- [ ] Black and White adjustment layer
- [ ] Posterize
- [x] Threshold
- [ ] Image > Mode > Grayscale


#### Q17. In the image shown, why is Sharpen Edges grayed out? (Ans 4)
<img src="https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot%20(440).png?raw=true">
- [ ] The filter doesn't work on a 16-bit image.
- [ ] The filer is not correctly installed.
- [ ] The filter doesn't work on a 32-bit image.
- [x] The filter requires a selection to be made first.


#### Q18. In the image shown, which Camera Raw feature was used to restrict the graduated filter to avoid the statue? 
<img src="https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot%20(443).png?raw=true">
- [x] Adjustment Brush
- [ ] Depth Range Mask
- [ ] Luminance Range Mask
- [ ] Color Range Mask


#### Q19. What can you use to save a common crop size? (Ans 4)
- [ ] tool sets
- [ ] preferences
- [ ] modifier keys
- [x] tool presets


#### Q20. Which Camera Raw Transform method is being used in the example shown? (Ans 1)
<img src= "https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot%20(442).png?raw=true">
- [x] Guided
- [ ] Vertical
- [ ] Level
- [ ] Full


#### Q21. To reduce the file size of a PDF, what should you do?

- [ ] Upsample large images
- [ ] Convert 8-bit images to 16-bit
- [x] Apply compression to the document
- [ ] all of these answers


#### Q22. Which image adjustment is null available as an adjustment layer?

- [ ] Levels
- [x] Shadows/Highlights
- [ ] Curves
- [ ] Hue/Saturation


#### Q23. With default Essentials settings, where would you find the Red Eye tool?

- [ ] grouped with the Eyedropped tool
- [ ] Image > Mode > Red Eye
- [ ] Edit > Red Eye
- [x] grouped with the Spot Healing Brush tool


#### Q24. Which option was <em>not</em> selected in the Magic Wand tool to create a selection like the one shown below?
<img src= "https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot.question24.png?raw=true">

- [x] Contiguous
- [ ] Anti-alias
- [ ] Auto-Enhance
- [ ] Sample All Layers


#### Q25. Where should you click to open a dialog box in which you can then choose to open a raw file as a Smart Object?
<img src= "https://github.com/ebazhanov/in-quiz-questions/blob/master/adobe-photoshop/image/Screenshot.question25.png?raw=true">

- [ ] A
- [ ] B
- [ ] C (I chose C, no idea if correct ;) )
- [ ] D


#### Q26. Which option would you use to clone while respecting perspective planes?

- [ ] Patch
- [x] Vanishing Point
- [ ] Clone Stamp
- [ ] Healing Brush


#### Q27. In order to run a filter on an entire video file, what must you do first?

- [ ] Convert the video file to an image sequence.
- [x] Convert the video file to a Smart Object.
- [ ] Actually, you cannot use filters on video files.
- [ ] Convert the video file to an animated gif.


#### Q28. Which option would you use to clone while respecting perspective planes?

- [ ] Patch
- [x] Vanishing Point
- [ ] Clone Stamp
- [ ] Healing Brush


#### Q29. Which file format does <em>not</em> support layers?

- [ ] Photoshop EPS
- [ ] Photoshop PDF
- [x] Large Document Format
- [ ] Photoshop PSD


#### Q30. Of these formats, which supports 16-bit images?

- [ ] JPEG
- [ ] GIF
- [x] PNG
- [ ] Photoshop EPS

#### Prove video link of my assignment done(passed >70%): https://www.youtube.com/watch?v=3TLGPOWE5SA&t=13s

