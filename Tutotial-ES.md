![WAZZAP](https://assets.cdn.filesafe.space/HZSeCeo66qW2JN9HroQv/media/d9739e2b-f7c8-485c-8567-ecd39dbb9688.png)


# 🎉 Nuevo Comando para Botones y Listas en el Sistema de Chat

¡Hola! 🎉 He creado dos nuevos comandos para nuestro sistema de chat que te permitirán enviar **botones** y **listas** de manera sencilla. A continuación, te explico cómo usarlos de forma clara y fácil:

---

## 📌 **Comandos Disponibles**

### 1. 🔘 **Comando de Botones**

**📄 Sintaxis:**

``` #Button|Texto del Mensaje|Opción1*id1/Opción2*id2/Opción3*id3```

**💡 Ejemplo:**

```#Button|Hola, ¿cómo estás?|Bien*d_bien/Mal*id_mal/Pesimo*id_pesimo```

**🔍 Explicación:**
- **#Button**: Indica que estás creando un mensaje con botones.
- **Texto del Mensaje**: El mensaje que verán los usuarios.
- **Opciones**: Las opciones de los botones se definen en el formato `Texto*id` y se separan con `/` si hay varias.

**📲 Resultado:**
Cuando el usuario elige una opción, en GHL aparecerá algo así:

```Button: id_mal```

```Mal```

Esto muestra el **tipo de botón**, el **ID** seleccionado y el **texto** del botón.

---

### 2. 📋 **Comando de Listas**

**📄 Sintaxis:**

```#List|Título|Descripción|Footer|Opción1*Subtítulo1*id1/Opción2*Subtítulo2*id2/Opción3*Subtítulo3*id3```

**💡 Ejemplo:**

```#List|Hola como estas|Dime la vdd|No seas timido|Bien*Perfecto*id_bien/Mal*Muy Mal*id_mai/Pesimo*Llorando*id_pesimo```

**🔍 Explicación:**
- **#List**: Indica que estás creando un mensaje con una lista.
- **Título**: El título de la lista.
- **Descripción**: Una breve descripción o instrucción.
- **Footer**: Información adicional al final del mensaje.
- **Opciones**: Las opciones de la lista se definen en el formato `Texto*Subtítulo*id` y se separan con `/` si hay varias.

**📲 Resultado:**
Cuando el usuario selecciona una opción, en GHL aparecerá algo así:

```List: id_mal ```

```Mal```

Esto muestra el **tipo de lista**, el **ID** seleccionado y el **texto** de la opción.

---

## 📝 **Resumen Rápido**

- **🔘 #Button**: Crea un mensaje con botones.
  - **Formato de opción**: `Texto*id`
  
- **📋 #List**: Crea un mensaje con una lista.
  - **Formato de opción**: `Texto*Subtítulo*id`

**✨ Tips:**
- Puedes agregar múltiples opciones separándolas con `/`.
- Asegúrate de seguir el formato correcto para que el sistema reconozca y procese tus comandos sin problemas.

---

¡Espero que esta guía te sea de gran ayuda! 🚀 Si tienes alguna duda o necesitas más asistencia, no dudes en contactarme. ¡Feliz desarrollo! 😊
