1. Run command:
   `npx create-react-app hello-tsx --typescript`

2. General list of unnecessary files is:
   ![image-20210221203950325](F:\My workspace\React Projects\typescript-quiz-app\React-Typescript Guide.assets\image-20210221203950325.png)

3. Simple React-Typescript Component looks like this:

   ```react
   import React, { FC } from 'react';
   import QuestionCard from './components/QuestionCard';
   
   const App: FC = () => {
     return (
       <div className="App">
         <QuestionCard />
       </div>
     )
   }
   
   export default App
   ```

   

