Download Link: https://assignmentchef.com/product/solved-operating-system-homework-5
<br>
Problems :

<ol>

 <li> What is the difference between a hard link and a symbolic link? Give an advantage of each one.</li>

 <li> A disk has 4000 cylinders, each with 8 tracks of 512 blocks. A seek takes 1 msec per cylinder moved.</li>

</ol>

If no attempt is made to put the blocks of a file close to each other, two blocks that are logically consecutive (i.e., follow one another in the file) will require an average seek, which takes 5 msec. If, however, the operating system makes an attempt to cluster related blocks, the mean interblock distance can be reduced to 2 cylinders and the seek time reduced to 100 microsec. How long does it take to read a 100 block file in both cases, if the rotational latency is 10 msec and the transfer time is 20 microsec per block?

<ol start="3">

 <li> Consider the following page reference string:</li>

</ol>

1, 2, 3, 4, 2, 1, 5, 6, 2, 1, 2, 3, 7, 6, 3, 2, 1, 2, 3, 6.

How many page faults would occur for the following replacement algorithms, assuming one, two, three, four, five, six, or seven frames? Remember all frames are initially empty, so your first unique pages will all cost one fault each.

<ul>

 <li>LRU replacement</li>

 <li>Optimal replacement</li>

</ul>

1

<ol start="4">

 <li> Consider a file currently consisting of 100 blocks. Assume that the file control block (and the index block, in the case of indexed allocation) is already in memory. Calculate how many disk I/O operations are required for contiguous, linked, and indexed (single-level) allocation strategies, if, for one block, the following conditions hold. In the contiguous allocation case, assume that there is no room to grow in the beginning, but there is room to grow in the end. Assume that the block information to be added is stored in memory.

  <ul>

   <li>The block is added at the beginning.</li>

   <li>The block is added in the middle.</li>

   <li>The block is added at the end.</li>

   <li>The block is removed from the beginning.</li>

   <li>The block is removed from the middle.</li>

  </ul></li>

 <li>A certain computer provides its users with a virtual-memory space of 2<sup>32 </sup> The computer has 2<sup>18 </sup>bytes of physical memory. The virtual memory is implemented by paging, and the page size is 4096 bytes. A user process generates the virtual address 11123456. Explain how the system establishes the corresponding physical location. Distinguish between software and hardware operations.</li>

</ol>

Programming Project

<ol>

 <li>Write a program in C or C++ that would map a text file into the main memory and that changes made by one instance of the program will be seen immediately by another instance of the program.</li>

</ol>