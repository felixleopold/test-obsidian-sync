# API Reference

## `AwesomeProject(options)`

Creates a new project instance.

### Parameters

| Name            | Type    | Required | Description            |
| --------------- | ------- | -------- | ---------------------- |
| `options.outDir`| string  | No       | Output directory       |
| `options.watch` | boolean | No       | Enable watch mode      |

### Returns

`AwesomeProject` instance.

### Example

```js
const project = new AwesomeProject({ outDir: './build', watch: true });
await project.build();
```

---

## `project.build()`

Runs the full build pipeline.

### Returns

`Promise<BuildResult>`

---

## `project.watch()`

Starts watching for file changes and rebuilds automatically.

### Returns

`Promise<void>`
