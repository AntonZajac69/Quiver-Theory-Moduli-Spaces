# Quiver-Theory-Moduli-Spaces
Database and Calculator of Moduli Spaces of Quiver Gauge Theories with 8 Supercharges.

The study of moduli spaces of supersymmetric quiver gauge theories is of paramount importance for the deeper understanding of string theory i.e. the hottest candidates for the unified theory of everything. 

Modern methods for the computation and study of such moduli spaces rely on the description of the Higgs and Coulomb branch of the moduli space as an algebraic variety. These varieties are computed from the spectrum of gauge invariant chiral operators which is conveniently ennumerated by a Hilbert series generating function. Hence, the information about the geometry of the moduli space is encoded in a Hilbert series and further analysis using algebraic methods is concievable.

Moduli spaces of supersymmetric theories with 8 supercharges in various dimensions enjoy one particularly powerful feature - they typically have associated brane embedding and can be constructed as COulomb branches of 3d N=4 susy gauge theories (examples of this construction include 3d Mirror symmetry and the notion of a magnetic quiver).

The present piece of Wolfram Mthematica code is called a quiver calculator. It allows the user to prescribe a 3d N=4 theory in the form of a quiver (editor) and then computes the corresponding Coulomb branch. The Coumputation of the Coulomb branch utilizes routines authored by Rudolph Kalveks. Furthermore, the geometrical structure of such moduli spaces (which are geometrically hyperKahler singularities i.e. symplectic singularities) has been shown to be encoded in a Hasse diagram by some of present author's collaborative works. Computation of the Hasse diagram for a quiver is included as a feature in the present code. Here, Antoine Bouget is to be acknowledged for the first routine which the algorithm of this feature is based on.

Test quivers which have been computed along the development are included in a form of a database of moduli spaces (database). All future computations using this code will have been stored and accessible by the next quiverist eager to use this utility.

It is hoped that some find this utilization handy in persuing further developments in geometry of moduli spaces of supersymmetric gauge theories.
