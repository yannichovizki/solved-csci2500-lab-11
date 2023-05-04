Download Link: https://assignmentchef.com/product/solved-csci2500-lab-11
<br>
<ol>

 <li><strong>Checkpoint 1: </strong>This lab focuses on material from Chapter 5 regarding cache memory. For the first checkpoint, download the c MIPS code. Walk through the code to understand what is expected overall.</li>

</ol>

Figuring out how many blocks (also known as slots or lines) exist in your direct-mapped cache is rather straightforward. To do so, determine how many possible index bit combinations exist. For example, with two bits, we have binary values 00, 01, 10, and 11, which is simply 2<sup>2</sup>.

Implement this in the block_count() function. Test with the cases shown in main(), but also be sure to add more test cases to ensure your code works.

<ol start="2">

 <li><strong>Checkpoint 2: </strong>For the second checkpoint, you will determine the index of a would-be cache entry via the get_index() More specifically, given an address, a starting point for your index, and the ending point of your index, implement logic in the get_index() function to find the appropriate index in a direct-mapped cache.</li>

</ol>

As with the previous checkpoint, test with the cases shown in main(), but also be sure to add more test cases to ensure your code works.

<ol start="3">

 <li><strong>Checkpoint 3: </strong>For the third checkpoint, you will determine the size of a cache block via the get_cache_block_size() More specifically, given the starting and ending point of your index as well as the block offset bits (BOBs), determine the total cache block size.</li>

</ol>

As with the previous checkpoints, test with the cases shown in main(), but also be sure to add more test cases to ensure your code works.