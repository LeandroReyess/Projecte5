# P02 — Llicenciament Windows Server 2025 💼🖥️

## Breu descripció

TransLògic S.A., empresa dedicada a la logística regional, vol renovar la seva infraestructura de servidors a **Windows Server 2025**. L’objectiu és virtualitzar tota la càrrega de treball per millorar la disponibilitat i facilitar la gestió.  

Actualment disposen d’un servidor físic amb 2 processadors de 12 nuclis cadascun (total 24 nuclis) i volen desplegar **12 màquines virtuals** per a diferents serveis:  

- 1 VM per a **Controlador de Domini (Active Directory)**  
- 1 VM per a **Servidor de Fitxers**  
- 1 VM per a **Servidor d'Impressió i Gestió Documental**  
- 1 VM per a **SQL Server (ERP)**  
- 8 VMs de suport per a aplicacions logístiques i terminals de magatzem  

**Usuaris i dispositius**:  
- 45 empleats: 30 d’oficina amb PC i portàtil, 15 mossos de magatzem que comparteixen 5 tauletes en 3 torns.  

L’encàrrec consisteix a **analitzar, calcular i proposar la millor solució de llicenciament** per aquesta infraestructura.

---

## Objectius del projecte

En completar aquest projecte hauràs après a:

1. Analitzar el **model de llicenciament per nucli** (core) de Windows Server 2025.  
2. Calcular el **cost total** segons les opcions: **Standard** i **Datacenter**.  
3. Determinar quin tipus de **CAL** (Client Access License: User vs Device) és més adequat.  
4. Justificar la solució final basant-se en:  
   - Costos  
   - Escalabilitat futura  
   - Funcionalitats avançades (ex. Storage Spaces Direct, SDN, virtualització infinita amb Datacenter).  
5. Preparar una **presentació per al client** (5-10 minuts) amb explicacions clares i accessibles per a un perfil no tècnic.  

---

## Procediment suggerit

1. **Analitzar les llicències**:  
   - Windows Server 2025 Standard vs Datacenter  
   - Costos per nucli (mínim de 8 nuclis per processador, 16 nuclis per servidor)  

2. **Calcular llicències CAL**:  
   - Comparar **User CALs** (per usuari) vs **Device CALs** (per dispositiu)  
   - Determinar la combinació més econòmica segons l’ús de l’empresa  

3. **Documentar resultats**:  
   - Crear taula comparativa amb costos totals  
   - Explicar funcionalitats que diferencien Standard de Datacenter  

4. **Preparar presentació**:  
   - Visuals clars i esquemes per explicar costos i avantatges  
   - Evitar terminologia tècnica complexa  

---

## Materials i links de suport

- [UD6.AA1 Introducció a Windows Server (Moodle)](Moodle 0224 SOX)  
- [Preus i llicències Windows Server (Microsoft)](https://www.microsoft.com/es-es/windows-server/pricing)  

---

💡 *Nota*: La decisió final ha de combinar **eficiència de costos, escalabilitat i cobertura de funcions avançades**. L’objectiu és que TransLògic pugui expandir el seu entorn virtual sense haver de tornar a licenciar cada cop que creixi.

