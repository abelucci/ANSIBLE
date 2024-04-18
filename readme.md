### **ANSIBLE**

---

Descargar el paquete previamente para poder realizar los playbooks.

---

Conexión hacia una VM linux en AZURE, creado por terraform:

* Crear la llave publica/privada en mi cliente ansible:

  ![1713383924860.png](./images/1713287216042.png)
* Copiar el contenido de la llave y pegarlo en la VM de azure, para poder agregar una conexion ssh nueva:

  ```
  cat ~/.ssh/id_rsa.pub
  ```
  ![1713383924860.png](./images/1713288017619.png)

  ![1713383924860.png](./images/1713287532871.png)
* Copiar la llave y enviarlo a la VM linux en AZURE:

  ![1713383924860.png](./images/1713287847553.png)
* Para comprobar que se haya copiado correctamente, se debe visualizar la llave en el siguiente path de la VM linux en AZURE:
* Verificamos la conexión:

  ![1713383924860.png](./images/1713287652543.png)
*
