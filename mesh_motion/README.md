This is a custom mesh motion solver as suggested in the cfd-online forums by Mr.Hassan Kassem. It combines the
angularOscillatingDisplacement with oscillatingDisplacement. Reference http://www.cfd-online.com/Forums/openfoam-verification-validation/151540-mesh-motion-not-consistent.html#post542969

Update:
Thanks to Mr.Hassan Kassem who shared his custom made mesh motion solver. I modified it slightly to suit the kinematics of kinsey and Dumas.

Translation is h = H*cos(wt);
Pitching motion is B = b*sin(wt);

Check out Mr.Hassans code here https://github.com/HIKassem/twoDOscillatingDisplacement
