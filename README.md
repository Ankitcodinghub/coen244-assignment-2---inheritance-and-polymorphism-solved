# coen244-assignment-2---inheritance-and-polymorphism-solved
**TO GET THIS SOLUTION VISIT:** [COEN244 Assignment 2 – Inheritance and Polymorphism Solved](https://www.ankitcodinghub.com/product/coen244-assignment-2-inheritance-and-polymorphism-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96236&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COEN244 Assignment 2 - Inheritance and Polymorphism Solved&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Q1. Class Reference

</div>
</div>
<div class="layoutArea">
<div class="column">
Implement a class, called Reference, to represent the characteristics that are common to all the References. Namely,

1. All references must have a unique identifier (of type int).

2. All references have a title and author (both of type string or char*), as well as year of publication (of type int);

Q2. Class Article

Article is a specialized Reference that also has information about the journal where the article is published, start page, and end page. More precisely,

1. An Article is a derived class of Reference

2. It also stores information about the journal (type string or char*), and the startPage and endPage (both of type int);

3. It implements the additional member function int getNumberOfPages(), which returns the total number of pages (computed using starPage and endPage);

Q3. Class Book

Book is also a specialized Reference that has information about the publisher of this reference. It also has number of pages as one of its attributes.

1. Book is a derived class of Reference

2. It stores the publisher (type string or char*) of this reference and the number of pages of this book (type int);

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. It also implements the member functions getNumberOfPages(), which returns the number of pages of this reference. In the case of Book reference, the number of pages is a single number, therefore, the member function simply returns this number;

4. It also implements functions related to the publisher.

Q4. Class TextBook

TextBook is a specialized Book. A textbook has an additional attribute, Web URL (Uniform Resource Locator (type string)), where students can find additional material such as slides, exercises, etc.

1. TextBook is a derived class of Book

2. It implements additional functions related to the setting and getting the URL

Q5. ReferenceManager

Create a class called ReferenceManager that will be used as a container to hold objects of classes Article, Book, and TextBook.

1. ReferenceManager has a fixed capacity. It uses a fixed size array to store References.

2. The first reference added to the container will be added at position zero, the second one at position 1, and so on. A reference is always added at the next available position;

3. A ReferenceManager has one regular constructor: ReferenceManager(int capacity). The constructor must create an array of size capacity, which will be used to store References. It will also initialize the instance variables that your implementation requires.

4. ReferenceManager will have size data member, which will track the number of references in the array.

5. bool add(Reference &amp; reference): adds a reference at the next available position and returns true, or returns false if the reference manager is full.

6. int get(int pos): returns the identifier of the Reference object stored at position pos of the ReferenceManager. You can assume that pos is a valid index, i.e. 0 &lt;= pos &lt; size;

7. bool Delete(int pos): removes the element at position pos of this ReferenceManager and returns true, or returns false if pos was not a valid index. It must also shift the elements of the array towards the beginning of the array;

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
8. bool search(int id); return true if the reference with identifier id exists, false otherwise

Key Notes:

All the classes should have

<ul>
<li>At least a default constructor, a copy constructor and a destructor</li>
<li>Accessing functions</li>
<li>A print function</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
