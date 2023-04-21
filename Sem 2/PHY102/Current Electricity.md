# 1.1 Current Density

* Electric current is charge in motion. 
* Current in a wire equals to the amount of charge passing through a fixed mark on the wire in unit time.
* Charge density is a given by:
$$\vec{J}=\sum n_iq_i\vec{u_i}$$ where n is particles per $m^3$ , q is charge and u is velocity
* For electrons, we get:
$$\vec{J_e}=-eN_e\vec{u_e}$$
Note: $-eN_e$ can be expressed as charged density of electrons( $\rho_e$ )

# 1.2 Charge Conservation
* Current flowing through any surface S is just the surface integral:
$$I=\int \vec{J}.d\vec{a}$$
* If current is steady, J must be constant in time everywhere.Thus it obeys charge conservation
* The surface integral of J over all of S gives the rate of charge leaving the volume.
* If Charge keeps flowing into or out of the volume, J blows up to infinity, unless some charge is created there continously. But that can never happen.
* Therefore we conclude that,in a **truly time-independent current distribution**, surface integral of J in any closed surface is zero. Or,
$$\nabla. \vec{J}=0$$


* Suppose current is not steady, then J is a function of t,x,y,z. Then, since J.da as integral is the rate at which charge leaves the volume and $\rho .dv$ is the total charge in the volume, we have:
$$\int_{S} \vec{J}.d\vec{a}=-\frac{d}{dt}\int_{S}\rho.dv $$
* By taking a infinitesimal small volume ( a point of x,y,z) the relation becomes
* **In time-dependent charge distributions**
$$\nabla.\vec{J}=-\frac{\partial{\rho}}{\partial{t}} $$
# Ohm's Law
* The linear relation between current density and Electric field is:
$$\vec{J}=\sigma \vec{E} $$
