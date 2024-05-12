# TS Initialiser

A Node.js library that simplifies the process of setting up a TypeScript project and initializing Git in the project directory.


## Installation

Navigate to your project directory and install ts-initialiser via npm:

```bash
  npm install ts-initialiser
```
    
## Usage

After installing ts-initialiser, run the following command:

```bash
npx ts-initialiser
```

This command will initialize TypeScript in your project and also perform a git initialization.
## TypeScript Configuration

By default, ts-initialiser sets up your tsconfig.json with the following configuration:

```json
{
  "compilerOptions": {
    "target": "es2016",
    "module": "commonjs",
    "rootDir": "./src",
    "outDir": "./dist",
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "strict": true,
    "skipLibCheck": true
  }
}

```