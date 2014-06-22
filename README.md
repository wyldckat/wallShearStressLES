wallShearStressLES
==================

Utility originally by the forum member Oscar Ochoa, for OpenFOAM 2.1.1: http://www.cfd-online.com/Forums/openfoam/103304-calculate-wall-shear-stress-of210-les-simulation-2.html#post467894
It's the one provided in the branch `OF21x`.

This git repository further adapts the utility for OpenFOAM 2.2.x and 2.3.x, done by Bruno Santos (wyldckat@github).


License
=======

The same as OpenFOAM(R), namely GNU GPL v3. For more information, see the file LICENSE.


Building on OpenFOAM 2.3.x, 2.2.x, 2.1.x
========================================

Using Git
---------

  1. Go to your user folder:

     ```
     mkdir -p $FOAM_RUN
     cd $FOAM_RUN/..
     ```

  2. Clone the repository and go into the cloned repository:

     ```
     git clone https://github.com/wyldckat/wallShearStressLES.git
     cd wallShearStressLES
     ```

  3. Checkout the repository respective to the version of OpenFOAM you are using:

   * OpenFOAM 2.3.x:

     ```
     git checkout OF23x
     ```

   * OpenFOAM 2.2.x:

     ```
     git checkout OF22x
     ```

   * OpenFOAM 2.1.x:

     ```
     git checkout OF21x
     ```

   4. Build `wallShearStressLES` by running:

     ```
     wmake
     ```


Using Zip
---------

  1. Go to your user folder:

     ```
     mkdir -p $FOAM_RUN
     cd $FOAM_RUN/..
     ```

  2. Get the Zip file for the repository respective to the version of OpenFOAM you are using:

   * OpenFOAM 2.3.x:

     ```
     wget https://github.com/wyldckat/wallShearStressLES/archive/OF23x.zip
     ```

   * OpenFOAM 2.2.x:

     ```
     wget https://github.com/wyldckat/wallShearStressLES/archive/OF22x.zip
     ```

   * OpenFOAM 2.1.x:

     ```
     wget https://github.com/wyldckat/wallShearStressLES/archive/OF21x.zip
     ```

   3. Unzip the respective file and go into the respective folder, for example:

     ```
     unzip OF23x.zip
     cd wallShearStressLES-OF23x
     ```
     
   4. Build `wallShearStressLES` by running:

     ```
     wmake
     ```
