# Optical Pumping Demo
A toy optical pumping simulation to help illustrate the optical pumping and de-pumping of rubidium. To see it in action take a look ovr here : http://www.alexvierich.com/Optical%20Pumping%20Demo

On the left is a rubidium lamp which emits right-hand circularly polarized light. The "Light Speed" slider will change the rate at which the light travels and is emitted by the lamp, this essentially speeds up or slows down the simulation.

On the sides of the rubidium cell are Helmholtz coils forming a horizontal magnetic field. This will induce Zeeman splitting of the rubidium energy levels with discreet M states. The "Magnetic Field" slider will increase or decrease this field.

Above and below the cell are another pair of Helmholtz coils applying a vertical RF field. These photons will re-thermalize the rubidium atoms when the Zeeman spacing matches their energy (It's about halfway on the Magnetic Field slider).

When the magnetic field is applied and the lamp is turned on, the electrons will follow the proper selection rules as they absorb photons and increase to the next energy level, note that since the photons are circularly polarized M must increase by +1. The electrons then spontaneously fall back down into the ground state with no preference of M level. It can be noticed that when the electrons fall into the M=+2 state, they are stuck, M cannot increase any further and the electrons will all congregate at this level. At this point, none of the photons are absorbed anymore and the cell becomes completely transparent.

This was a demo which was put together very quickly with JavaScript, feel free to modify and use as you please. I hope this helps people better understand the principles of optical pumping!
