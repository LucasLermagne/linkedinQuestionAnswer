C++ Assessment
---------------------
#### What is printed from this code?
```
vector<int>; v(22);
bool b = (v[6]);
printf ("%d", !b);
```
- [ ] FALSE
- [ ] This code has an error.
- [ ] 0
- [ ] 1

#### What is a class template?

- [ ] It is a class written with the generic programming paradigm, specifying behavior in terms of type parameters rather than specific types.
- [ ] It is a skeleton source code for a class where the programmer has to fill in specific parts to define the data types and algorithms used.
- [ ] It is a class that consists only of member variables, with no constructor, destructor, or member functions.
- [ ] It is a blank superclass intended for inheritance and polymorphism.

#### Which STL class is the best fit for implementing a collection of data that is always ordered so that the pop operation always gets the greatest of the elements? Suppose you are interested only in push and pop operations.

- [ ] std::list
- [ ] std::priority_queue
- [ ] std::vector
- [ ] std::map

#### What is this expression equivalent to?
A->B->C->D

- [ ] *(*((*A).B).C).D
- [ ] A.B.C.D
- [ ] *A.*B.*C.*D
- [ ] &A.&B.&C.&D

#### What is null in this code?
```
typedef struct{
    unsigned int  age    : 4;
    unsigned char gender : 1;
    unsigned int  size   : 2;
}child_t;
```

- [ ] It is a type defined as a structure with bit fields, with 4 bits for age, 1 bit for gender, and 2 bits for size.
- [ ] It is a type defined as a structure with three unsigned fields initialized as age=4, gender=1, and size=2.
- [ ] This code causes a compiler error because the colon character is not allowed in struct definitions.
- [ ] It is a type defined as a structure with three arrays. The size and length of these arrays are age: int[4], gender:char[1], and size:int[2], all unsigned.

#### Which choice is null a difference between a class and a struct?

- [ ] Template type parameters can be declared with the null keyword, but not with the null keyword.
- [ ] The default access specifier for members of structs is public, whereas for members of classes, it is private.
- [ ] Because structs are part of the C programming language, there is some compatibility between C and C++ using structs. This is not the case with classes.
- [ ] Classes can have member functions; structs cannot.

#### Which choice shows the contents of vectors pointed by v1 and v2 after running this code?
```
std::vector &lt;int&gt; *v1 = new std::vector &lt;int&gt; ({1,2,3});
std::vector &lt;int&gt; *v2;
v2=v1;
v1-&gt;push_back(4);
v2-&gt;push_back(5);
```

- [ ] *v1: {1,2,3,4,5}; *v2: {1,2,3,4,5}
- [ ] *v1: {1,2,3,4}; *v2: {1,2,3,5}
- [ ] ERROR
- [ ] *v1: {1,2,3,4}; *v2: {5}

#### What is an appropriate way of removing null as shown below?
my_class *my_object = new my_class();

- [ ] free(my_object);
- [ ] delete(my_object);
- [ ] The garbage collector will destroy the object eventually.
- [ ] Exiting the scope will destroy the object.

#### Which operator is overloadable?
- [ ] ?:
- [ ] .
- [ ] new
- [ ] ::

#### Why does the null receive a function object as one of its parameters?

- [ ] std::sort operates on a template container. The compiler does not know how to relationally compare the values it contains, so a function must be provided to do the comparison.
- [ ] std::sort will use the parameter function as an error handler. The function will be called if an error occurs.
- [ ] The std::sort function is a template. The programmer is free to enter the sorting algorithm in a function object as an argument.
- [ ] Actually, std::sort takes only one argument, which is the container to be sorted.

#### What would be the output of this code?
```
int i0=4, i1=6, i2=8;
int&amp; nums[3]={i2,i0,i1};
std::cout&lt;&lt;nums[0]&lt;&lt;nums[1]&lt;&lt;nums[2];
```

- [ ] The output is the addresses of i2, i0, and i1, in that order, with no spaces.
- [ ] 846
- [ ] 468
- [ ] There is no output. The code causes a compiler error because nums is an array of references, which is illegal.

#### You want to have several lines of code that print out some variables for debugging purposes, but you do not want those lines to make it to the final application, for efficiency reasons. Which choice achieves the desired behavior producing the shortest possible code length, regardless of the level of optimization used?

- [ ] // set the following to false for the final application
bool debugging = true;

// copy and customize this for every debugging line
if(debugging){
 cout&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
}
- [ ] // copy and customize this for every debugging line
 cerr&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
- [ ] #define DEBUGGING(x)  #include x 

// copy and customize this for every debugging line

DEBUGGING(
 cout&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
)
- [ ] // comment the following line for the final application
#define DEBUGGING

// copy and customize this for every debugging line
#ifdef DEBUGGING
 cout&lt;&lt;"Var1 = "&lt;&lt;var1&lt;&lt;endl;
#endif

#### Which choice is the correct declaration for a class named Dog, derived from the Animal class?
```
class Animal{
 //...
};
```

- [ ] class Dog : public Animal{
 //...
};
- [ ] class Dog :: public Animal{
 //...
};
- [ ] public class Dog extends Animal{
 //...
};
- [ ] public class Animal::Dog{
 //...
};