## Reflexión personal

Desde mi experiencia como estudiante de ciberseguridad trabajando con herramientas como **Kali Linux, Burp Suite** y verificando aplicaciones contra **OWASP ASVS**, he aprendido que **los riesgos están intrínsecamente ligados a las características de la aplicación**:

**El simulador de lavadero es "a prueba de balas" por diseño** - su minimalismo lo protege naturalmente. Sin embargo, si esta misma lógica se desplegara como **aplicación web conectada** con usuarios reales, pagos y datos de vehículos, escalaría inmediatamente a ASVS Nivel 2-3.

Las **aplicaciones críticas** (banca, salud) enfrentan amenazas dirigidas constantes que justifican inversiones masivas en seguridad: MFA, cifrado end-to-end, WAF, threat modeling continuo. Un solo fallo en estas puede resultar en **multas AEPD de millones de euros** (art. 5.1.f RGPD) además del daño reputacional irreparable.