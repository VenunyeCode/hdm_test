# hdm_test
An internship technical test

During the test, i have created another use case which is CheckTaskExistenceUseCase. The purpose of this use case is to implement the DRY pattern. I've noticed that if I want to edit or delete a task, I need to check if the task exists before. To avoid repetition, I created this use case and call it when it's needed.

I have used POSTMAN to test the API because it's the recommended tool to test APIs. 

In the Web App, I have used states to manage datas and the "Add task" form.
When the user clicks on the "Ajouter une tâche" form, a form is automatically displayed to let the user enter the data.

In the code, I've used the trim function to avoid nullables datas like spaces or check if the user has entered datas.


