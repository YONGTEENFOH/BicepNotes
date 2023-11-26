Bicep Expressions = To allow certain values to be referenced to another files
![image](https://github.com/YONGTEENFOH/BicepNotes/assets/56257279/d0491d5d-09ad-45dc-a326-f1b5e5bdee4a)

Bicep parameters = used to pass dynamic values into a template to make it flexible and reusable.
The following types are available:
string
object
array
int
bool

example:
![image](https://github.com/YONGTEENFOH/BicepNotes/assets/56257279/ce60906e-762c-4a53-8669-eda8462268e7)


Bicep variables = to determine the value
![image](https://github.com/YONGTEENFOH/BicepNotes/assets/56257279/7ed5f28a-0398-4fc6-a97b-477311f09cd3)


Ternary statements
![image](https://github.com/YONGTEENFOH/BicepNotes/assets/56257279/271772ba-d44a-4648-bd8a-e917f8905d41)


How to deploy bicep templates:
![image](https://github.com/YONGTEENFOH/BicepNotes/assets/56257279/f9b38470-3d51-495e-b255-64c0e5b6b5fb)


when to use param vs var?
Also notice that you're using a variable for the Azure App Service plan name, but you're using parameters for the other names. Storage accounts and App Service apps need globally unique names, but App Service plan names need to be unique only within their resource group. This difference means it's not a concern to use the same App Service plan name across different deployments, as long as the deployments are all going into different resource groups.
