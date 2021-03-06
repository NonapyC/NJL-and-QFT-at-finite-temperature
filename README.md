# NJL-and-QFT-at-finite-temperature
Reviewing the chiral symmetry breaking at finite density and temperature in the Nambu-Jona-Lasinio model. The lagrangian which I use in this review has a SU(2)×SU(2) symmetry.

## NLJ Lagrangian
First, we review the Nambu-Jona-Lasinio model[1]:

![texclip20200504002813](https://user-images.githubusercontent.com/54795218/80918115-31519200-8d9e-11ea-895b-24f9d65d269e.png)

Where G is the coupling constant and the degree of freedom is spinor. This lagrangian has U(1) symmetry. In this review, We caluculate the physical mass m*. According to the QFT, the poles of the two-point correlation function correspond to the physical mass:

<img width="435" alt="スクリーンショット 2020-05-04 0 40 22" src="https://user-images.githubusercontent.com/54795218/80918475-24ce3900-8da0-11ea-9b91-3a24bc55738a.png">

So, we can find the physical mass by caluculating the self-energy of this lagrangian. 

The equation by which we seek the physical mass m* of this lagrangian is called gap equation. If the coupling constant exceeds the threshold, vacuum transition occurs and the symmetry is broken. And then quark gain the own mass.

## SU(2)×SU(2) symmetry
We extend NJL lagrangian to SU(2)×SU(2) symmetric theory[2]. In this review, we take the number of flabours is 2, and number of coulors is 3:

![texclip20200504010502](https://user-images.githubusercontent.com/54795218/80919154-7af0ab80-8da3-11ea-9115-2605a488529c.png)

where the degree of freedom is quark:

![texclip20200504010338](https://user-images.githubusercontent.com/54795218/80919091-19c8d800-8da3-11ea-982a-794e7ba30929.png)

and we introduce the 2×2 pauri matrix on flavaor space. (u,d) indicates flavor, (R,G,B) indicates color and (0,1,2,3) indicates spinor.

To find the quark physical mass, we calculate the self-energy:

<img width="577" alt="スクリーンショット 2020-05-04 1 10 58" src="https://user-images.githubusercontent.com/54795218/80919378-9ad49f00-8da4-11ea-9fe0-6f6fbcdf0854.png">

### QCD diagram
We introduce the temperature by using the half-periodicity of imaginary time and can calucurate the quark mass by using finite temperature propagater which is standard methods used in modern field theory.

This figure shows the phase diagram of QCD at each given density and temperature.

![NJL](https://user-images.githubusercontent.com/54795218/80917760-167e1e00-8d9c-11ea-94c3-155ea3b19e56.png)

## Refarence
[1]Y.Nambu and G.Jona-Lasinio. Phys. Rev. 122.345 (1961).

[2]M.Asakawa and K.Yazaki, Nuci, Phys. A 504, 668 (1989).
