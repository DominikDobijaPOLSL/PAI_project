# PAI_project
## Table Of Contents
- [Description](##Discription)
- [Tech Stack](##Tech-Stack)
- [Screenshots](##Screenshots)
- [Local Building](##Local-Building)
- [How to Contribute](##How to Contribute)

## Discription 
The aim of this project is to present an OpenSource library "Babylon.js" used to render graphics. The idea is to show the possibilities offered by the engine and to use it to animate graphics on a sample web service   

## Tech Stack
- [Babylon.js 4.2](https://www.babylonjs.com/) for web rendering engines.
- [Babylon.js documentation](https://doc.babylonjs.com/)
- [Poly Haven](https://polyhaven.com/) for find and download object.
- [Blender](https://www.blender.org/)
- [Node.js](https://nodejs.org/en/docs/)

## Screenshots
### polyhaven.com

<img src="/screenshots/polyhaven.jpg" alt="Vue Expenses Dashnoard" width="100%" />

### Blender

<img src="/screenshots/blender.jpg" alt="Vue Expenses Dashnoard" width="100%" />

### Implementation
 
1. Home

<img src="/screenshots/imp1.jpg" alt="Vue Expenses Dashnoard" width="100%" />

2. Pictures

<img src="/screenshots/imp2.jpg" alt="Vue Expenses Dashnoard" width="100%" />

3. Contact

<img src="/screenshots/imp3.jpg" alt="Vue Expenses Dashnoard" width="100%" />

4. *.glb objects

<img src="/screenshots/imp4.jpg" alt="Vue Expenses Dashnoard" width="80%" />

<img src="/screenshots/imp5.jpg" alt="Vue Expenses Dashnoard" width="80%" />

<img src="/screenshots/imp6.jpg" alt="Vue Expenses Dashnoard" width="80%" />

<img src="/screenshots/imp7.jpg" alt="Vue Expenses Dashnoard" width="80%" />

<img src="/screenshots/imp8.jpg" alt="Vue Expenses Dashnoard" width="80%" />

## Local Building
1. Download project
2. Install [Node.js](https://nodejs.org/en/download/)
3. Open command prompt in downloaded directory
4. Install packages by `npm install`
5. To start the server at `http://localhost:8080/`, enter `node server.js`
6. You can add your own `*.glb` objects. 

## How to Add Your own `*.glb` file
### Download file
You can download file for example from [Poly Haven](https://polyhaven.com/)

### Prepare file
1. Prepare your model for export in Blender.
2. Export the mesh from Blender.
3. Import and prepare the FBX file in Substance Painter.
4. Export the glTF file from Substance Painter.
5. Create a * file.

[Link to instruction](https://help.shopify.com/en/partners/resources/creating-media/3d-models/creating-3d-models/blender)

### Add file to source path directory
1. Add creating`*.glb` file to source path directory.
2. Modyfy `.html` files (menu) to create a possibility to open your  `*glb` file.


## How to Contribute
1. Clone repo `git clone https://github.com/DominikDobijaPOLSL/OiRPOS_project.git`.
2. Create a new branch: `git checkout -b new_branch_name`.
3. Make changes and test.
4. Submit Pull Request with description of changes.

