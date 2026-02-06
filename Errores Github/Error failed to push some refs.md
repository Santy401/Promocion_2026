### 1️⃣ Traer los cambios del remoto

La forma más segura es hacer un **pull** primero para integrar los cambios:

`git pull origin master`

- Esto trae los cambios del remoto y los mezcla con los tuyos.
    
- Si hay conflictos, Git te pedirá resolverlos antes de poder hacer push.
    

---

### 2️⃣ Resolver conflictos (si aparecen)

- Git marcará los archivos con conflictos con `<<<<<<< HEAD` y `>>>>>>> branch`.
    
- Abre esos archivos, elige qué parte quieres conservar y guarda.
    
- Luego haz:
    

`git add . git commit -m "Resolviendo conflictos"`

---

### 3️⃣ Hacer push otra vez

Después de actualizar tu rama local y resolver conflictos:

`git push origin master`

¡Ahora debería funcionar!

---

⚠️ **Atajo peligroso**: Si estás seguro de que quieres **sobrescribir todo lo remoto** con tu local (borrando lo que haya en remoto):

`git push origin master --force`

Pero ojo: esto elimina cambios en remoto que no tengas localmente, así que úsalo solo si sabes lo que haces.