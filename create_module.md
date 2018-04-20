# Creating a Component with Ionic

1- In the Ionic project folder, open the terminal and run:
  ```bash
    ionic g component test
  ```
  - A folder will be created inside of `src/components`;
  - The file `test.module.ts` can be deleted.
  
2- Import the component into the file `src/app/app.modules.ts`:  
  ```typescript
    import {Test} from '../components/test/test'; 
  ```
  - At the command above write the component path first. It will help to fill the component's name inside the `{}` 
  
3- In the same file `src/app/app.modules.ts`, declare the component in the attribute `declarations`;

4- To use the component, just insert its tag (`<test></test>`) in the tamplate desired.
