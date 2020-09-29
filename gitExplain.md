// Merge and Rebase

// M1

Master  m1 -> m2 -> m3 
               |
               V
features       m2 -> f1 -> f2

Master Combined 

        m1 -> m2 -> m3 -> ?

// ====> Local computer Head, because I reverted once to m2 
<<<<<<< HEAD
m1
m2
m3
<<<<<<< HEAD
// ====> Local computer Head 

=======

// => this is current git location, m2 
>>>>>>> parent of ece6085... m2



Below is remote computer version(in github),
the git location in remote computer 
=======


Local Computer reverted to m2 

Remote Project also changed with new commit
>>>>>>> 3e14fb6480f8e07e2ae3df40874e7eea45565398
