This is almost the original ADVENTURE source, written by Will Crowther and unearthed by Dennis G. Jerz. These files have been minimally modified to compile under GNU g77. The data files have been converted to fixed-field format based on a tab width of 7 and one (erroneous?) blank line has been removed from each. 


To compile

g77 -o advf4-11 -finit-local-zero advf4-11.f advsup.f
g77 -o advf4-31 -finit-local-zero advf4-31.f advsup.f

This version accepts lowercase characters, and does not reproduce a bug in two-word-command handling in the 1977-03-11 version, but should otherwise play identical to the original. 
