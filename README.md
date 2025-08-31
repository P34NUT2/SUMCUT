<h1 align="center">SUMCUT</h1>

###

<div align="center">
  <img height="400" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2c4aW1yM200dmU4YWtvdWxpZjczZWF0dmd6emFxMnI5ZWFhMmJtOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LNiNkrJKhUaA6BaI2O/giphy.gif"  />
</div>

###

<p align="left"></p>

###

<h2 align="left">About This Proyect</h2>

###

<p align="left">Our project focuses on developing an artificial intelligence that functions as an academic assistant, with the objective of optimizing the way students generate and organize notes. To achieve this, we have planned it in two implementation phases.<br>In the first phase, we will work with a pre-trained model, which will serve as a base to transform a reduced set of main ideas or questions into a complete and well-structured note. The dynamic will be simple: the user will only need to write two or three central ideas from the class or some questions that have arisen, and the artificial intelligence will be responsible for elaborating a complete text that not only answers those questions, but also expands related information. The final result will be an academic note that includes a clear development of the topic, relevant definitions, practical explanations and, complementarily, links to YouTube videos and other resources that reinforce content comprehension. This way, the student will be able to save time, obtain quality information and have a tool that promotes autonomous learning.<br><br>The second phase seeks to go one step further by eliminating the need for the user to input ideas in writing. At this level, the artificial intelligence will have the capability to activate through the device's microphone, listen to the class in real time and, once it ends, automatically generate a complete note. To achieve this, the AI will transcribe the audio, detect the main ideas presented by the professor, organize the concepts in a structured manner and, like in the first phase, complement with clear explanations, examples and links to digital resources that strengthen topic understanding.<br>In summary, this project presents a practical solution to one of students' greatest challenges: taking quality notes while paying attention to class. In the initial phase, the tool will function as a note generator from key ideas, and in the advanced phase it will evolve toward an assistant capable of listening, understanding and synthesizing class information in real time. With this, we not only seek to save time, but also elevate the learning level, improve knowledge retention and offer an innovative resource that adapts to current education needs.</p>

###

<h2 align="left">code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="40" alt="bash logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" height="40" alt="pytorch logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" height="40" alt="tensorflow logo"  />
</div>

###
<p align="left"> 
  <h2 align="left">Tecnologías </h2>
 • Backend: TypeScript, Node.js, Prisma ORM
 • Base de datos: PostgreSQL
 • Frontend: React, TypeScript
 • IA: Python, PyTorch, TensorFlow
 • DevOps: Docker, Bash

Arquitectura Backend

La implementación del backend se realiza con TypeScript y Prisma como ORM, utilizando PostgreSQL como base de datos principal. Esto permite una gestión eficiente y segura de los datos académicos generados por la plataforma.

Instalación
 1. Clona el repositorio:git clone https://github.com/P34NUT2/SUMCUT.git
cd SUMCUT

 2. Instala dependencias en la carpeta backend:npm install

 3. Configura la base de datos PostgreSQL en el archivo ‎`.env`.
 4. Ejecuta migraciones con Prisma:npx prisma migrate dev

 5. Inicia el servidor:npm run dev
</p>

###
<h2 align="left"> Documentación : </h2>
<p align="left"> 
  
- https://www.prisma.io/docs/
- https://www.postgresql.org/docs/
</p>

###
<h2 align="left"> Markdown </h2>

<p align"left"> 
## Uso de PostgreSQL y Prisma

### Configuración inicial

1. **Instala PostgreSQL**  
   Descarga e instala PostgreSQL desde [postgresql.org](https://www.postgresql.org/download/).

2. **Crea una base de datos**
   ```bash
   createdb sumcut
###
<h2 align="left"> Instala Prisma y genera la configuración </h2>

```
npm install prisma --save-dev
npm install @prisma/client
npx prisma init
```
###
<h2 align="left"> Configura la conexión en .env </h2>

###
```
DATABASE_URL="postgresql://usuario:contraseña@localhost:5432/sumcut"
```
</p>

<h2 align="left"> Modelado y migraciones </h2>

```
model Note {
  id        Int      @id @default(autoincrement())
  title     String
  content   String
  createdAt DateTime @default(now())
  updatedAt DateTime @updatedAt
}
```
  
###

<h2 align="left"> Crear y ejecutar una migración </h2>

```
npx prisma migrate dev --name init
```
###
  
<h2 align="left"> Generar el cliente Prisma </h2>

```
npx prisma generate
```
  
###
  
<h2 align="left"> Comandos útiles de Prisma </h2>
<p align="left"> Ver el estado de la base de datos. </p>

```
npx prisma studio
```

<p align="left"> Sincronizar modelos sin migración (SOLO DESARROLLO) </p>

```
npx prisma db push
```
<p align="left"> Revertir migraciones </p>

```
npx prisma migrate reset
```
  
###

<h2 align="left">Team:</h2>

###

<p align="left">-Manuel Oyamburu: Frontend and Backend (specialized in Frontend)<br>-Diego D'Maurice: Frontend and Artificial Intelligence<br>-Andoreni Flores Alcocer: Backend (specialized in Backend)<br>-Antonio Villafaña: Artificial Intelligence and Backend (specialized in AI)</p>

###
