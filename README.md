## Impulsive Manoeuvres: Interplanetary Trajectory from Earth to Mars

Code for NASA's General Mission Analysis Tool (GMAT)

Spacecraft: Human Mars Lander (HML)

Transfer method: B-plane targeting 

## Design Requirements
• The HML shall undergo an interplanetary transfer from Earth to Mars.

• The HML shall arrive in the Martian orbit before MAVERIC does on the 19th of June 2040.

## Assumptions
• The initial hyperbolic orbit before the deep space manoeuvre will be achieved through the use of a direct insertion from a launch or alternative method external to the HML.

• Specific launch site is not necessary for this initial analysis.

## Mathematical Models, Implementation and Software
The B-Plane targeting method is a planar coordinate system that allows the HML to target the ideal orbit around Mars during a gravity assist as shown in Figure 1 [1]. The transfer starts with a hyperbolic orbit, then performs a deep space manoeuvre, also called a Trajectory Correction Manoeuvre (TCM), and then once the HML is near Mars it will perform a capture manoeuvre into the Martian Orbit [1]. As mentioned in Reference 1, “The first target sequence employs manoeuvres in the Earth-based Velocity (V), Normal (N) and Bi-normal (B) directions and includes four propagation sequences. The purpose of the manoeuvres in VNB directions is to target BdotT and BdotR components of the B-vector. [1]”. 

![image](https://github.com/user-attachments/assets/7acfc3f7-8621-4876-960a-957334a4d8ed)

Figure 1. B-Plane Targeting [1]

## GMAT Script Results

![image](https://github.com/user-attachments/assets/2cd1d47d-d189-499c-8387-cbf5873dc828)

Figure 2. GMAT Results of Direct Insertion from Earth


![image](https://github.com/user-attachments/assets/26dcf043-9cc7-4bdf-865a-4c3d1d59fafe)

Figure 3. GMAT Results of Deep Space Manoeuvre and Transfer from Earth to Mars


![image](https://github.com/user-attachments/assets/cd598780-9b24-487c-b3ef-4339976d173e)

Figure 4. GMAT Results of Mars Capture at MAVERIC's Orbit

## References

[1] SourceForge. Chapter 8. Mars B-Plane Targeting. Accessed: September 2023. Online: SourceForge; 2023.
