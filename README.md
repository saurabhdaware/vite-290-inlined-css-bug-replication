# Replication for https://github.com/vitejs/vite/issues/7913

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/github-12zodn-vbxsug)

### Replicating Bug Locally

- Clone this repo
- Install dependencies\

```sh
yarn
```

- Start Dev Server\

```sh
yarn dev
```

- The Output will not have red background even though it is mentioned in inlined css of `index.html` file.

#### Actual Output

<img width="449" alt="image" src="https://user-images.githubusercontent.com/30949385/165339314-033b616d-386e-468e-aded-bfaf727386f5.png">

#### Expected Output

<img width="443" alt="image" src="https://user-images.githubusercontent.com/30949385/165339533-93fe7580-367e-42d7-b974-8c33666d049d.png">
