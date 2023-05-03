Download Link: https://assignmentchef.com/product/solved-cs2100-tutorial-11-cache
<br>
D1.  ]

A machine with a word size of 16 bits and address width of 32 bits has a <strong>directmapped cache</strong> with 16 blocks and a block size of 2 words, initially empty.

<ul>

 <li>Given a sequence of memory references as shown below, where each reference is given as a byte address in both decimal and hexadecimal forms, indicate whether the reference is a hit (H) or a miss (M).</li>

</ul>

<table width="486">

 <tbody>

  <tr>

   <td colspan="2" width="228"><strong>Memory address </strong></td>

   <td rowspan="2" width="102"><strong>Hit (H) or Miss (M)? </strong></td>

   <td rowspan="2" width="156"><strong>(For reference) </strong></td>

  </tr>

  <tr>

   <td width="96"><strong>(in decimal) </strong></td>

   <td width="132"><strong>(in hexadecimal) </strong></td>

  </tr>

  <tr>

   <td width="96">4</td>

   <td width="132">0x4</td>

   <td width="102"><strong>M</strong></td>

   <td width="156">0000 … 0000 0100</td>

  </tr>

  <tr>

   <td width="96">92</td>

   <td width="132">0x5C</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 0101 1100</td>

  </tr>

  <tr>

   <td width="96">7</td>

   <td width="132">0x7</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 0000 0111</td>

  </tr>

  <tr>

   <td width="96">146</td>

   <td width="132">0x92</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 1001 0010</td>

  </tr>

  <tr>

   <td width="96">30</td>

   <td width="132">0x1E</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 0001 1110</td>

  </tr>

  <tr>

   <td width="96">95</td>

   <td width="132">0x5F</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 0101 1111</td>

  </tr>

  <tr>

   <td width="96">176</td>

   <td width="132">0xB0</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 1011 0000</td>

  </tr>

  <tr>

   <td width="96">93</td>

   <td width="132">0x5D</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 0101 1101</td>

  </tr>

  <tr>

   <td width="96">145</td>

   <td width="132">0x91</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 1001 0001</td>

  </tr>

  <tr>

   <td width="96">264</td>

   <td width="132">0x108</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 1 0000 1000</td>

  </tr>

  <tr>

   <td width="96">6</td>

   <td width="132">0x6</td>

   <td width="102"><strong> </strong></td>

   <td width="156">0000 … 0000 0110</td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Given the above sequence of memory references, fill in the final contents of the cache. Use the notation M[<em>i</em>] to denote the word starting at memory address <em>i</em>, where <em>i</em> is in hexadecimal. If a block is replaced, cross out the content in the cache and write the new content over it.</li>

</ul>

<table width="456">

 <tbody>

  <tr>

   <td width="72"><strong>Index </strong></td>

   <td width="96"><strong>Tag value </strong></td>

   <td width="145"><strong>Word 0 </strong></td>

   <td width="143"><strong>Word 1 </strong></td>

  </tr>

  <tr>

   <td width="72">0</td>

   <td width="96"> </td>

   <td width="145"> </td>

   <td width="143"> </td>

  </tr>

  <tr>

   <td width="72">1</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">2</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">3</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">4</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">5</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">6</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">7</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">8</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">9</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">10</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">11</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">12</td>

   <td width="96"><strong> </strong></td>

   <td width="145"><strong> </strong></td>

   <td width="143"><strong> </strong></td>

  </tr>

  <tr>

   <td width="72">13</td>

   <td width="96"> </td>

   <td width="145"> </td>

   <td width="143"> </td>

  </tr>

  <tr>

   <td width="72">14</td>

   <td width="96"> </td>

   <td width="145"> </td>

   <td width="143"> </td>

  </tr>

  <tr>

   <td width="72">15</td>

   <td width="96"> </td>

   <td width="145"> </td>

   <td width="143"> </td>

  </tr>

 </tbody>

</table>

<strong><em>Tutorial Questions </em></strong>

<ol>

 <li>Here is a series of address references in decimal: 4, 16, 32, 20, 80, 68, 76, 224, 36, 44, 16, 172, 20, 24, 36, and 68 in a MIPS machine. Assuming a <strong>direct-mapped cache</strong> with 16 one-word blocks that is initially empty, label each address reference as a hit or miss and show the content of the cache.</li>

</ol>

You may write the data word starting at memory address X as M[X]. (For example, data word starting at memory address 12 is written as M[12]. This implies that the word includes the 4 bytes of data at addresses 12, 13, 14 and 15.) You may write the tag values as decimal numbers. If a block is replaced in the cache, cross out the corresponding content in the cache, and write the new content over it.







<ol start="2">

 <li>Use the series of references given in question 1 above: 4, 16, 32, 20, 80, 68, 76, 224, 36, 44, 16, 172, 20, 24, 36, and 68 in a MIPS machine. Assuming a <strong>two-way set-associative cache</strong> with two-word blocks and a total size of 16 words that is initially empty, label each address reference as a hit or miss and show the content of the cache. Assume <strong>LRU</strong> replacement policy.</li>

</ol>

You may write the data word starting at memory address X as M[X]. (For example, data word starting at memory address 12 is written as M[12]. This implies that the word includes the 4 bytes of data at addresses 12, 13, 14 and 15.) You may write the tag values as decimal numbers. If a block is replaced in the cache, cross out the corresponding content in the cache, and write the new content over it.

























<ol start="3">

 <li>Although we use only data memory as example in the cache lecture, the principle covered is equally applicable to the instruction memory. This question takes a look at both the instruction cache and data cache.</li>

</ol>

The code below is from Tutorial 3 Question 1 (<strong><em>palindrome checking</em></strong>) with the following variable mappings:

low → $s0,   high→ $s1, matched → $s3, base of string[]→ $s4, size → $s5

<table width="557">

 <tbody>

  <tr>

   <td width="47"><strong># </strong></td>

   <td width="255"><strong>Code </strong></td>

   <td width="255"><strong>Comment </strong></td>

  </tr>

  <tr>

   <td width="47"><strong>i0 i1 i2 i3 </strong><strong> i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 </strong><strong> i14 i15 </strong><strong> i16 </strong><strong> i17 </strong></td>

   <td width="255"> <strong>[some instruction]</strong>  <strong>addi $s0, $zero, 0  addi $s1, $s5, -1  addi $s3, $zero, 1 </strong><strong>loop:    </strong><strong> slt  $t0, $s0, $s1  beq  $t0, $zero, </strong><strong>exit</strong><strong>  beq  $s3, $zero, </strong><strong>exit</strong><strong>  add  $t1, $s4, $s0  lb   $t2, 0($t1)  addi $t3, $s4, $s1  lb   $t4, 0($t3)  beq  $t2, $t4,</strong><strong> else</strong><strong>  addi $s3, $zero, 0 </strong><strong> j    </strong><strong>endW</strong><strong>  </strong><strong>else:  </strong><strong> addi $s0, $s0, 1  addi $s1, $s1, -1 </strong><strong>endW:</strong><strong>  </strong><strong> j    </strong><strong>loop</strong> <strong>exit:</strong><strong>  </strong><strong> [some instruction]</strong></td>

   <td width="255"><strong><em> </em></strong><strong># low = 0 </strong><strong># high = size-1 </strong><strong># matched = 1 </strong><strong>  </strong><strong># (low &lt; high)? </strong><strong># exit if (low &gt;= high) </strong><strong># exit if (matched == 0) </strong><strong># address of string[low] </strong><strong># t2 = string[low] </strong><strong># address of string[high] </strong><strong># t4 = string[high] </strong><strong> </strong><strong># matched = 0 </strong><strong># can be “j loop” </strong><strong> </strong><strong># low++ </strong><strong># high— </strong><strong> </strong><strong># end of while </strong> </td>

  </tr>

 </tbody>

</table>

<strong>Parts (a) to (d) assume that instruction i0 is stored at memory address </strong><strong>0x0.  </strong>

<ul>

 <li>Instruction cache: <strong>Direct mapped with 2 blocks of 16 bytes each</strong> (i.e. each block can hold 4 consecutive instructions).</li>

</ul>

Starting with an empty cache, the fetching of instruction i1 will cause a cache miss. After the cache miss is resolved, we now have the following instructions in the instruction cache:

<table width="450">

 <tbody>

  <tr>

   <td width="204">Instruction Cache Block 0</td>

   <td width="246">[i0, <strong>i1</strong>, <strong>i2</strong>, <strong>i3</strong>]</td>

  </tr>

  <tr>

   <td width="204">Instruction Cache Block 1</td>

   <td width="246">[empty]</td>

  </tr>

 </tbody>

</table>

Fetching of i2 and i3 are all cache hits as they can be found in the cache.

Assuming the string being checked is a palindrome. Show the instruction cache block content <strong>at the end of the 1<sup>st</sup> iteration (i.e. up to instruction i16). </strong>

<strong> </strong>

<strong>             </strong>

<ul>

 <li>If the loop is executed for a total of 10 iterations, what is the total number of cache hits (i.e. after the 10<sup>th</sup> “j loop” is fetched)?</li>

</ul>

<strong> </strong>

<ul>

 <li>Suppose we change the instruction cache to:</li>

 <li><strong>Direct mapped with 4 blocks of 8 bytes each</strong> (i.e. each block can hold 2 consecutive instructions).</li>

</ul>

Assuming the string being checked is a palindrome. Show the instruction cache block content <strong>at the end of the 1<sup>st</sup> iteration (i.e. up to instruction i16). </strong>

<table width="450">

 <tbody>

  <tr>

   <td width="204">Instruction Cache Block 0</td>

   <td width="246"> </td>

  </tr>

  <tr>

   <td width="204">Instruction Cache Block 1</td>

   <td width="246"> </td>

  </tr>

  <tr>

   <td width="204">Instruction Cache Block 2</td>

   <td width="246"> </td>

  </tr>

  <tr>

   <td width="204">Instruction Cache Block 3</td>

   <td width="246"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<ul>

 <li>If the loop is executed for a total of 10 iterations, what is the total number of cache hits (i.e. after the 10<sup>th</sup> “j loop” is fetched)?</li>

</ul>




Let us now turn to the study of <strong>data cache</strong>. We will assume the following scenario for parts (e) to (g):

<ul>

 <li>The string being checked is <strong>64-character long</strong>. The first character is located at location <strong>0x1000</strong>.</li>

 <li>The string is a palindrome (i.e. it will go through 32 iterations of the code).</li>

</ul>




<ul>

 <li>Given a <strong>direct mapped data cache with 2 cache blocks, each block is 8 bytes</strong>, what is the final content of the data cache at the end of the code execution (after the code failed the beq at i5)? Use <strong>s[X..Y]</strong> to indicate the data <strong>string[X]</strong> to <strong>string[Y].</strong></li>

</ul>

<table width="450">

 <tbody>

  <tr>

   <td width="180">Data Cache Block #0</td>

   <td width="270"> </td>

  </tr>

  <tr>

   <td width="180">Data Cache Block #1</td>

   <td width="270"> </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>What is the hit rate of (e)? Give your answer in a fraction or a percentage correct to two decimal places.</li>

</ul>




<ul>

 <li>Suppose the string is now <strong>72-character long</strong>, the first character is still located at location <strong>0x1000</strong> and the string is still a palindrome, what is the hit rate at the end of the execution?</li>

</ul>