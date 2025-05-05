# cs2210-assignment-2-multimedia-ordered-dictionary-solved
**TO GET THIS SOLUTION VISIT:** [CS2210 Assignment 2-Multimedia Ordered Dictionary Solved](https://www.ankitcodinghub.com/product/cs2210-assignment-2-multimedia-ordered-dictionary-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95847&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2210 Assignment 2-Multimedia Ordered Dictionary Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment you will implement a multimedia ordered dictionary that allows repeated keys using a binary search tree.

1 Classes to Implement

You need to implement the following Java classes: MultimediaItem, NodeData, BSTNode, BSTOrderedDictionary, and Query. You can implement more classes if you need to. You must write all the code yourself. You cannot use code from the textbook, the Internet, or any other sources: however, you may implement the algorithms discussed in the lectures.

1.1 Class BSTNode

This class represents the nodes of the binary search tree implementing the ordered dictionary. This class has the following instance variables:

<ul>
<li>􏰀 &nbsp;BSTNode parent: a reference to the parent of this node</li>
<li>􏰀 &nbsp;BSTNode leftChild: a reference to the left child of this node</li>
<li>􏰀 &nbsp;BSTNode rightChild: a reference to the right child of this node</li>
<li>􏰀 &nbsp;NodeData data: a reference to the information stored in this node.
This class must have the following two constructors:
</li>
</ul>
<ul>
<li>􏰀 &nbsp;BSTNode(): creates a new BSTNode object in which all its instance variables have value null. This constructor is used when creating a leaf node.</li>
<li>􏰀 &nbsp;BSTNode(BSTNode newParent, BSTNode newLeftChild, BSTNode newRightChild, NodeDatanewData): creates a new BSTNode in which the instance variables take the values specified in the corresponding parameters.
For this class you must implement all and only the following public methods:

<ul>
<li>􏰀 &nbsp;BSTNode getParent(): returns the parent of this node</li>
<li>􏰀 &nbsp;BSTNode getLeftChild(): returns the left child of this node</li>
<li>􏰀 &nbsp;BSTNode getRightChild(): returns the right child of this node</li>
<li>􏰀 &nbsp;NodeData getData(): returns the NodeData object stored in this node</li>
<li>􏰀 &nbsp;setParent(BSTNode newParent): sets the parent of this node to the specified value</li>
<li>􏰀 &nbsp;setLeftChild(BSTNode newLeftChild): sets the left child of this node to the specified value</li>
<li>􏰀 &nbsp;setRightChild(BSTNode new rightChild): sets the right child of this node to the specified value</li>
<li>􏰀 &nbsp;setData(NodeData newData): stores the given NodeData object in this node</li>
<li>􏰀 &nbsp;boolean isLeaf(): returns true if this node is a leaf; returns false otherwise.
You can implement any other methods that you want to in this class, but they must be declared as private methods (i.e. not accessible to other classes).
</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.2 Class NodeData

This class represents the data items that will be stored in the internal nodes of the binary search tree implementing the ordered dictionary. Remember that in a leaf node the data and children are null, but the parent is not null, unless the leaf node is the root of the tree. Each object of this class will have two instance variables:

<ul>
<li>􏰀 &nbsp;String name: this is the key attribute for the data stored in a node.</li>
<li>􏰀 &nbsp;ArrayList&lt;MultimediaItem&gt;media: list of multimedia objects associated with the key at-
tribute of this node.

The constructor for this class must be of the following form:
</li>
</ul>
􏰀 NodeData(String newName): creates a new NodeData object with the given key attribute and an empty media list.

For this class you must implement all and only the following public methods:

<ul>
<li>􏰀 &nbsp;void add(MutimediaItem newItem): adds newItem to the media list of this object</li>
<li>􏰀 &nbsp;String getName(): returns the name attribute of this object.</li>
<li>􏰀 &nbsp;ArrayList&lt;MultimediaItem&gt; getMedia(): returns the media list stored in this object.
You can implement any other methods that you want to in this class, but they must be declared as private methods.
</li>
</ul>
1.3 Class MultimediaItem

This class represents each one of the multimedia objects stored in the arrayList of a node of the binary search tree. This class has two instance variables:

<ul>
<li>􏰀 &nbsp;String content: a descriptor of the multimedia content. This could be text, the name of an audio file, the name of an image file, or the name of an html document.</li>
<li>􏰀 &nbsp;int type: the type of information represented by instance variable content. The values that this instance variable can take are these:
– 1: if content is text

– 2: if content is the name of an audio file

– 3: if content is the name of an image file

– 4: if content is the name of an html document.

The constructor for this class must be of the following form:
</li>
</ul>
􏰀 MultimediaItem(String newContent, int newType): creates a new MultimediaItem ob ject whose instance variables have the values specified by the parameters.

For this class you must implement all and only the following public methods:

<ul>
<li>􏰀 &nbsp;String getContent(): returns the content of this node.</li>
<li>􏰀 &nbsp;int getType(): returns the type of this node.
You can implement any other methods that you want to in this class, but they must be declared as private methods.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1.4 Class BSTOrderedDictionary

This class implements an ordered dictionary using a binary search tree. In the binary search tree only the internal nodes will store information. The key for an internal node will be the name attribute of the NodeData object stored in that node. To implement this class, you need to declare it as follows:

public class BSTOrderedDictionary implements BSTOrderedDictionaryADT

This class has these instance variables:

<ul>
<li>􏰀 &nbsp;BSTNode root: the root of the binary search tree.</li>
<li>􏰀 &nbsp;int numInternalNodes: the number of internal nodes in this tree. The constructor for this class must be of the following form</li>
</ul>
􏰀 BSTOrderedDictionary(): creates an empty BSTOrderedDictionary in which the root is a leaf BSTNode and numInternalNodes = 0.

In this class you must implement all the public methods specified in the OrderedDictionaryADT interface:

<ul>
<li>􏰀 &nbsp;BSTNode getRoot(): returns the root of this tree.</li>
<li>􏰀 &nbsp;int getNumInternalNodes(): returns the value of numInternalNodes.</li>
<li>􏰀 &nbsp;ArrayList&lt;MultimediaItem&gt; get (BSTNode r, String key): finds in the tree with root r the BSTNode with the given key attribute key and it returns the list of MultimediaItem ob jects stored in it; it returns null if no node in the tree stores the given key.</li>
<li>􏰀 &nbsp;void put (BSTNode r, String key, String content, int type): adds the given infor- mation to the tree with root r. We will allow the tree to store more than one data item with the same key attribute: If the tree already has a node p with key attribute equal to key then a new MultimediaItem object storing the given content and type is added to the ArrayList stored in p. If the tree does not have a node storing key then a new internal node is added to the binary search tree containing a NodeData object with key attribute key and an ArrayList storing a MultimediaItem object containing the given content and type.
If a new internal node is created the value of numInternalNodes must be increased.
</li>
<li>􏰀 &nbsp;void remove(BSTNode r, String key) throws DictionaryException: removes from the binary search tree with root r the BSTNode storing the given key attribute key. The method throws a DictionaryException if no node stores the given key.
If an internal node was removed, the value of numInternalNodes must be decreased.
</li>
<li>􏰀 &nbsp;void remove(BSTNode r, String key, int type) throws DictionaryException: re- moves from the tree with root r all MultimediaItem objects of the type specified by the third parameter stored in the ArrayList of the node with key attribute key. If after removing these MultimediaItem objects the ArrayList becomes empty, the BSTNode with key attribute key must be removed from the tree.
If no node has key attribute key then this method must throw a DictionaryException. If an internal node was removed, the value of numInternalNodes must be decreased.
</li>
<li>􏰀 &nbsp;NodeData smallest(BSTNode r): returns the NodeData object storing the smallest key in the tree with root r; returns null if the tree is empty.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;NodeData largest(BSTNode r) throws DictionaryException: returns the NodeData ob- ject storing the largest key in the tree with root r; returns null if the tree is empty.</li>
<li>􏰀 &nbsp;NodeData successor (BSTNode r, String key): returns the NodeData objects stored in the successor of the node storing key attribute key in the tree with root r; returns null if the successor does not exist.</li>
<li>􏰀 &nbsp;NodeData predecessor (BSTNode r, String key): returns the NodeData objects stored in the predecessor of the node storing key attribute key in the tree with root r; returns null if the predecessor does not exist.
You can implement any other methods that you want to in this class, but they must be declared as private methods.
</li>
</ul>
1.5 Class Query

This class implements a text-based application that allows the user to access the information in the multimedia ordered dictionary. This class contains the main method, declared with the usual method header:

public static void main(String[] args)

The input to the program will be a file containing the information that is to be stored in the ordered dictionary. Therefore, to run the program you will type this command:

java Query inputFile

where inputFile is the name of the file containing the input for the program. Your main method must read the input file and it will store the information stored in the input file in the binary search tree specified in the previous section. Section 1.5.2 specifies the format of the input file.

After reading the input file and creating the corresponding BSTOrderedDictionary your main method will have a loop in which it will repeatedly ask the user to enter a command which the program will process as explained below; the loop will end when the user enters the command end.

To read user commands you must use method

String read (String label)

from the provided StringReader class. It is very important that you use this method, as otherwise the TA’s will not be able to test your program. The above method prints on the screen the label supplied as parameter and then it reads one line of input from the keyboard; the line read is returned as a String to the invoking method. So, for example, to ask the user to type a command you might use this code fragment in your program:

StringReader keyboard = new StringReader();

String line = keyboard.read(“Enter next command: “);

1.5.1 User Commands

The commands that the user can enter and which your program must process are explained below.

􏰀 get k

If the BSTOrderedDictionary has a node p with key attribute k, then each one of the MultimediaItem objects in the ArrayList stored in that node will be processed in the fol- lowing manner. Let D be one of these MultimediaItem objects:

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;if D.type = 1, then your program must print D.content on the screen,</li>
<li>– &nbsp;if D.type = 2, then your program must play the audio file whose name is stored in
D.content,
</li>
<li>– &nbsp;if D.type = 3, then your program must display the image stored in the file whose name
is stored in D.content.
</li>
<li>– &nbsp;if D.type = 4 , then your program must display the web page specified in D.content.
If there is no node with key attribute k then the program must print the message: Key k is not in the ordered dictionary

and then it must print (i) the key attribute of the predecessor of p (if p has a predecessor), and (ii) the key attribute of the successor of p (if p has a successor).

So, for example, consider an ordered dictionary storing the following NodeData objects. We denote a NodeData object as [key,&lt;(content1,type1),(content2,type2),…&gt;].
</li>
</ul>
<ul>
<li>– &nbsp;[“computer”,&lt;(“An electronic machine frequently used by Computer Science
students”,1),(“computer.gif”,3)&gt;]
</li>
<li>– &nbsp;[“flower”,&lt;(“flower.html”,4)&gt;]</li>
<li>– &nbsp;[“tree”,&lt;(“tree.jpg”,3),(“tree.gif”,3)&gt;]</li>
<li>– &nbsp;[“ping”,&lt;(“ping.wav”,2)&gt;]</li>
<li>– &nbsp;[“matrix”,&lt;(“matrix.gif”,3)&gt;]
If in the above ordered dictionary the user enters the command get ping your program must play the file “ping.wav”. If the user enters the command get computer, your program it must print the text “An electronic machine frequently used by Computer Science students” and it must display the image in file “computer.gif”. For the command get flower your program must display the content of the webpage “flower.html”.

If the user enters the command get homework your program should print the following:

The word homework is not in the ordered dictionary. Preceding word: flower

Following word: matrix

If the user enters the command get abacus your program should print:

The word abacus is not in the ordered dictionary. Preceding word:

Following word: computer
</li>
</ul>
<ul>
<li>􏰀 &nbsp;remove k

Removes from the ordered dictionary the node with key attribute k, or if no node stores this

key your program must print

No record in the ordered dictionary has key k.
</li>
<li>􏰀 &nbsp;delete k t
If a node p with key attribute k is in the tree, this command must delete from the ArrayList of p all the MultimediaItem objects with type t. For example the command delete computer 3 will remove from the above dictionary the MultimediaItem object (computer.gif,3) from the node storing key attribute “computer”. If after removing these MultimediaItem objects the ArrayList is empty, then node p must be removed.

If no node stores the key k then your program must print No record in the ordered dictionary has key k.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;addkct
If no node in the tree stores key k then a new node p with that key is added to the tree; otherwise your program finds the node p storing key k. A MultimediaItem storing content c and type t is added to the ArrayList of p.
</li>
<li>􏰀 &nbsp;nextkd
This command must find the node p with key attribute k or, if this node does not exist, the leaf node p where the key attribute k should have been stored. Then your program must find the d successor nodes of p (if they exist) and print the key attribute of p (if p is an internal node) and the key attributes of the d successors (if they exist) in lexicographic increasing order.

For example, for the ordered dictionary described above, if the user enters next computer 2, your program must print

computer flower matrix

If the user enters next ab 1, your program must print computer

If the user enters next ping 3, your program must print ping tree

If the user enters next vet 2, your program must print There are no keys larger than or equal to vet
</li>
<li>􏰀 &nbsp;prevkd
This command must find the node p with key attribute k or, if this node does not exist, the leaf node p where the key attribute k should have been stored. Then your program must find the d predecessor nodes of p (if they exist) and print the key attribute of p (if p is an internal node) and the key attributes of the d predecessors (if they exist) in lexicographic decreasing order.

For example, for the ordered dictionary described above, if the user enters prev computer 2, your program must print

computer

If the user enters prev ab 1, your program must print “There are no keys smaller than or equal to set” If the user enters prev ping 3, your program must print ping matrix flower computer
</li>
<li>􏰀 &nbsp;first

This command must print the smallest key attribute in the ordered dictionary. For example,

for the above ordered dictionary the command first must print: computer. If the ordered dictionary is empty your program must print

The ordered dictionary is empty.
</li>
<li>􏰀 &nbsp;last

This command must print the largest key attributes in the ordered dictionary. For example,

for the above ordered dictionary the command last must print: tree. If the ordered dictionary is empty your program must print

The ordered dictionary is empty.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;size
This command prints the number of internal nodes in the binary search tree implementing the ordered dictionary. For example, for the above ordered dictionary the command size must print

There are 5 keys in the ordered dictionary
</li>
<li>􏰀 &nbsp;end
This command terminates the program.
</li>
<li>􏰀 &nbsp;If an invalid command is entered your program must print the message
<pre>     Invalid command
</pre>
</li>
</ul>
1.5.2 Format of the Input File

The input file is a text file. The first line contains a string; this is the key attribute of the first NodeData object q to be stored in the ordered dictionary. The second line is a string s that is processed as follows:

<ul>
<li>􏰀 &nbsp;If s is the name of an audio file then a MultimediaItem object with attributes content = s and type = 2 is created and stored in the ArrayList of q.</li>
<li>􏰀 &nbsp;If s is the name of an image file then a MultimediaItem object with attributes content = s and type = 3 is created and stored in the ArrayList of q.</li>
<li>􏰀 &nbsp;If s is the name of an html file then a MultimediaItem object with attributes content = s and type = 4 is created and stored in the ArrayList of q.</li>
<li>􏰀 &nbsp;Otherwise, a a MultimediaItem object with attributes content = s and type = 1 is created and stored in the ArrayList of q.
A node storing q is created and set as the root of the tree.

Each pair P of lines in the rest of the input file is processed in the same manner: the first line in the pair specifies a key attribute and the second line specifies the content of a MultimediaItem object. Note that if a node already exists with the same key attribute as specified by the first line in a pair then no new BSTNode is created, instead the MultimediaItem corresponding to the second line in the pair P is added to the ArrayList of that node.

If the second line of a pair P contains only one string of the form x.y, thena MultimediaItem object is created with attribute content = x.y and type as specified below:

<ul>
<li>􏰀 &nbsp;if y = “wav” or y = “mid” then type = 2. We will consider only audio files with these two extensions.</li>
<li>􏰀 &nbsp;if y = “jpg” or y = “gif” then type = 3. We will consider only these two types of image files.</li>
<li>􏰀 &nbsp;ify=”html”thentype=4.
If the second line l of a pair P is not of the gorm x.y then a new MultimediaItem object is created with attributes content = l and type = 1.

For example, the above ordered dictionary could be constructed with the following input file:
</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
matrix

matrix.gif

computer

An electronic machine frequently used by Computer Science students flower

<pre>   flower.html
   tree
   tree.jpg
   tree
   tree.gif
   computer
   computer.gif
   ping
   ping.wav
</pre>
and the corresponding binary search tree is shown in the following figure.

</div>
</div>
<div class="layoutArea">
<div class="column">
NodeData

</div>
<div class="column">
matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
BSTNode

</div>
</div>
<div class="layoutArea">
<div class="column">
ArrayList

matrix.gif, 3

</div>
<div class="column">
MultimediaItem

null

</div>
</div>
<div class="layoutArea">
<div class="column">
tree

</div>
</div>
<div class="layoutArea">
<div class="column">
computer

</div>
</div>
<div class="layoutArea">
<div class="column">
null

</div>
<div class="column">
flower

flower.html,4

</div>
<div class="column">
tree.gif,3 tree.jpg,3 computer.gif, 3

An electronic …, 1

null null

</div>
<div class="column">
ping

null

</div>
</div>
<div class="layoutArea">
<div class="column">
null

</div>
</div>
<div class="layoutArea">
<div class="column">
1.5.3 Important Notes and Classes Provided

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;The main method is public static void main(String[] args): the name of the input file will be stored in args[0].</li>
<li>􏰀 &nbsp;The key attribute of each node must be converted to lower case before being stored in the dictionary, so that capitalization does not matter when looking for a key in the dictionary.</li>
<li>􏰀 &nbsp;To play an audio file you must use the provided Java class SoundPlayer.java; you will use method play(String fileName) to play the named audio file.</li>
<li>􏰀 &nbsp;To display an image, you must use the provided Java class PictureViewer.java; you will use method show(String fileName) to display a .jpg or .gif file.</li>
<li>􏰀 &nbsp;To display a webpage you must use the provided Java class ShowHTML.java; you will use method show(String url) to render the page on the screen.</li>
<li>􏰀 &nbsp;A MultimediaException will be thrown by methods play, run and show of classes SoundPlayer.java, PictureViewer.java, and Show HTML.java if the named files cannot be found or if they cannot be processed. Your program must catch these exceptions and print appropriate messages.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
<div class="layoutArea">
<div class="column">
ping.wav,2

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
We provide you with a java class called Sample.java that illustrates how to use methods play,

run and show from the above classes. Study this class so you know how to use these methods. 􏰀 If you use Eclipse, to ensure that it will find all the image, sound, html, and txt files, put all these files in the same directory; then in Eclipse go to Run, Run Configurations, select Arguments, on Working directory select ”Other” and click on ”File System” and choose the

directory that contains your files.

Hint. You might find useful the StringTokenizer Java class and methods toLowerCase() and

endsWith(String prefix) from class String. 2 Testing your Program

We will run a test program called TestDict to check that your implementation of BSTOrderedDictionary has the properties specified above. We will supply you with a copy of TestDict to test your implementation. We will also run other tests on your software to check whether it works properly.

3 Coding Style

Your mark will be based partly on your coding style. Among the things that we will check, are

<ul>
<li>􏰀 &nbsp;Variable and method names should be chosen to reflect their purpose in the program.</li>
<li>􏰀 &nbsp;Comments, indenting, and white spaces should be used to improve readability.</li>
<li>􏰀 &nbsp;No instance variable should be used unless they contain data which is to be maintained in the
object from call to call. In other words, variables which are needed only inside methods, whose values do not have to be remembered until the next method call, should be declared inside those methods.
</li>
<li>􏰀 &nbsp;All instance variables should be declared private, to maximize information hiding. Any access to these variables from other classes should be done with accessor methods.</li>
</ul>
</div>
</div>
</div>
