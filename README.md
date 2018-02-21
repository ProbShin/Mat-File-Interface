# A project for manipulate `Matlab Mat File Format` using c++
This is a project collected the materials and codes for me during the study of reading/writing `Matlab mat file format` using c++. All the codes and materials are free to use. If there is anything happenly be helpful for you, would you leave us a comments, added us friends or give us a star? :P

# Usage
Just download and include `MatIO.h`, `MatIO.cpp`. 

# Useful Materials and Links
[Matlab Official Materials in Pdf](https://www.mathworks.com/help/pdf_doc/matlab/matfile_format.pdf "Matlab Official Materials")  
[Mat Format wiki like Introduction](http://fileformats.archiveteam.org/wiki/MAT)

The official c interface example files are installed under 
`
matlabroot/extern/examples/eng_mat
`

# What's the Matlab binary Mat File Format? *.mat
A MAT-file stores data in binary (not human-readable) form.  

# What's the features of Matlab binary Mat File Format?
* The advantage are: The file is small in size and fast to read and write.(This is especially useful for large files. I have a large matrix stored into matrix market format which is 12T and takes me 2~4 hours to read into memory, however stored in binray format, it is ?T and takes me 15 minutes to lead into memory.)   
It is simple to use for Matlab user. Just using `save` and `load` command.

* The disadvantage are: The file is Not human-readable.(We cannot use text editor to open/edit it).  
Offical interface API for other languages (i.e. C,C++,Fortran,...) requires Matlab pre-installed.

# Whether to use Matlab binary Mat File Format?
If you had to write/read varibales stored into *Mat File Format*.   
1. The first recommanded choice would be using *Matlab*.(i.e. `save`,`load`).  
2. Another choice is to use the *mat API functions* from the Matlab library (e.g., `matOpen`, `matGetVariable`, etc):
3. The next choice would be use *Python `Scipy`,???*.
4. The last choice would be use our/your own codes.


# You are welcome to contribute.
Please leave us comments, star or watch if you there is anything you might feel useful.

This project is under construction.
We are going to support python later.
