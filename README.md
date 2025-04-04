# 👨‍💻 DarkChris11

¡Hola! Soy **Christian**, un apasionado de la tecnología, con formación en:

🎓 **Grado Superior en Administración de Sistemas Informáticos en Red (ASIR)**  
🧠 **Especialización en Inteligencia Artificial y Big Data**

---

## 💡 Sobre mí

Soy un desarrollador curioso, creativo y con muchas ganas de aprender. Me encanta explorar nuevas tecnologías, construir soluciones útiles y participar en proyectos que desafíen mis habilidades.

Mi pasión por la **automatización** y la **creación/gestión de servidores** me impulsa a buscar siempre formas de mejorar y optimizar procesos.

---

## 🛠️ Tecnologías que domino

- **Lenguajes**: Python 🐍, JavaScript ⚡, Bash (Linux) 🐚  
- **Bibliotecas**: React ⚛️, Pandas 📊, TensorFlow 🧠  
- **Frameworks**: Django 🌱, Bootstrap 🎨  
- **Bases de datos**: MySQL 🐬, PostgreSQL 🐘

---

## 🚀 Pasión por la automatización y servidores

Uno de mis intereses más grandes es la **automatización** de tareas y la **gestión de servidores**. Ya sea configurando servidores desde cero, gestionando su infraestructura o creando scripts para hacer todo más eficiente, siempre busco maneras de optimizar el tiempo y reducir errores mediante la automatización.

---

## 🧑‍💻 Código de mi perfil (representado en clases Python)

```python
class DarkChris11:
    def __init__(self):
        self.nombre = "Christian Benvenutto"
        self.educacion = ["Grado Superior en ASIR", "Especialización en Inteligencia Artificial y Big Data"]
        self.habilidades = ["Python", "JavaScript", "Bash (Linux)", "React", "Django", "TensorFlow", "Pandas", "MySQL", "PostgreSQL"]
        self.contacto = {
            "LinkedIn": "https://www.linkedin.com/in/christian-benvenutto/",
            "Twitter": "https://x.com/Christi95650587",
            "Email": "benvenuttocaler@gmail.com"
        }
    
    def descripcion(self):
        return f"Soy {self.nombre}, un desarrollador con formación en {', '.join(self.educacion)}."

    def mostrar_habilidades(self):
        return f"Habilidades: {', '.join(self.habilidades)}"

    def mostrar_contacto(self):
        return "\n".join([f"{k}: {v}" for k, v in self.contacto.items()])

# Instanciando la clase y mostrando información
dark_chris = DarkChris11()
print(dark_chris.descripcion())
print(dark_chris.mostrar_habilidades())
print(dark_chris.mostrar_contacto())
