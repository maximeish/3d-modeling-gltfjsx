# Glasses GLTF 3D Model configurator using React Three Fiber

![](glasses.png)

## How to use

1. Set up [react-three-fiber](https://github.com/pmndrs/react-three-fiber)

2. Compress model (.glb or .gltf) to optimise it for the web
   `npx gltf-pipeline -i your-model.gltf -o output-model.glb --draco.compressionLevel=10`

3. Generate JSX component from the optimized model
   `npx gltfjsx output-model.glb`

4. Put the generated JSX component anywhere inside `/src`

5. Put the `output-model.glb` in `/public`

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified, the filenames include the hashes, and it is ready to be deployed.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
