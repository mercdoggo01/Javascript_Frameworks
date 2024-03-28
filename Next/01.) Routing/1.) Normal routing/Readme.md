Basic routing tutorial

Objective:

To learn about routing in Next js


Steps:

1.) Create a Next js app ----> type in terminal npx create-next-app@latest

2.) Create folder with some name (which will be your route) ----> insert one js file called page and export if just like in React (demonstrated below)

eg.) 
        const Faq = () => {
             return (
                     <div>
                         <p>This is about FAQ page.</p>
                     </div>)
        }
        export default Faq

3.) Run in local host ---> npm run dev

4.) Verify if route is working ----> localhost:3000/(your route name)
