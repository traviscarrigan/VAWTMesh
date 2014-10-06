# VAWTMesh
A Glyph script to generate a complete mesh for a vertical axis wind turbine simulation.

![ScriptImage](https://raw.github.com/traviscarrigan/VAWTMesh/master/ScriptImage.png)

## Usage
The script can either generate or import airfoil geometry. You can then specify how many blades, the rotor specifics, boundary layer mesh parameters, and finally the farfield mesh parameters. The script will generate the 2D VAWT geometry and automatically assemble the grid. The grid is built for a sliding mesh calculation with a rotating inner zone and stationary outer zone. 

