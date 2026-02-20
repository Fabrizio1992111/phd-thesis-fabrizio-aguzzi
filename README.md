
En esta tesis se desarrolla y valida un marco multiescala para predecir el comportamiento termomecánico de componentes nucleares fabricados con aleaciones de circonio (Zircaloy-2). La implementación acopla el modelo viscoplástico autoconsistente (VPSC) —capaz de representar creep y crecimiento bajo irradiación, creep térmico y expansión térmica a nivel cristalino— con la plataforma de elementos finitos Code\_Aster. Esta integración transfiere la física constitutiva desde la microestructura hacia un análisis estructural completo, vinculando textura cristalográfica y respuesta global.

Se desarrolló un esquema automatizado para rotar tensores de tensión y deformación entre el sistema global del FEM y los ejes cristalográficos de cada grano, funcionalidad no disponible originalmente en Code\_Aster. Además, se recupera analíticamente la deformación elástica mediante la inversa del tensor de rigidez autoconsistente provisto por VPSC.

La capacidad predictiva del marco se demuestra mediante la simulación de un conjunto combustible tipo PWR, incluyendo el contacto no lineal entre la grilla espaciadora y el tubo de revestimiento de Zircaloy-2. Los resultados reproducen fenómenos complejos y confirman la influencia dominante de la textura en la respuesta anisotrópica.

Se identificó que texturas con alta fracción de planos prismáticos orientados en la dirección normal reducen la separación y el desgaste entre componentes. Los mecanismos térmicos gobiernan la relajación inicial, mientras que los inducidos por irradiación dominan a largo plazo.

En conjunto, la tesis presenta una plataforma computacional abierta y extensible para analizar el desempeño de combustibles nucleares, permitiendo simulaciones de alta fidelidad bajo condiciones combinadas de carga térmica, mecánica y de irradiación.



This thesis develops and validates a multiscale modeling framework to predict the thermomechanical behavior of nuclear components made of Zircaloy-2. The approach couples the viscoplastic self-consistent (VPSC) model —capable of representing irradiation creep and growth, thermal creep, and thermal expansion at the crystal level— with the finite element platform Code\_Aster. This integration transfers the constitutive physics from the microstructural scale to a full structural analysis, linking crystallographic texture to the global response.

An automated tensor-rotation scheme between the global FEM system and each grain’s crystallographic axes was implemented, together with an analytical recovery of elastic deformation via the inverse of the VPSC stiffness tensor.

The predictive capability is demonstrated through the simulation of a Pressurized Water Reactor (PWR) fuel-assembly case, reproducing nonlinear contact between spacer grid and cladding tube. Results highlight the role of crystallographic texture in the anisotropic mechanical response.

Textures with a high fraction of prism planes aligned with the grid’s normal direction reduce component separation and wear. Thermal mechanisms dominate the initial stress relaxation, while irradiation-induced effects prevail in the long term.

Overall, the thesis introduces an open and extensible computational framework for high-fidelity nuclear-fuel simulations under combined thermal, mechanical, and irradiation loads.
