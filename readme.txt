Enterprise Architect ColdFusion Code Generation MDG Technology.

This project is based on the work of http://devnulled.com/content/2005/09/modified-coldfusion-template-for-enterprise-architect/

I took that MDG technology and added ColdFusion 9 support for ORM entities, inheritance, interfaces and more.

To Install:

* Close all projects
* Create a folder somewhere in your maching called MDGTechnologies.  I have done mine in the desktop and I have dropped the templates there.
* On EA go to settings > MDG Technologies.
* Click on Advanced and then click on add and choose Add Path..., then choose the directory you created
* Click ok and restart EA.  Now coldfusion is available for any project

To Install the CF9 reference templates do the following:

* Click on Tools > Import Referecne Data and choose the cf9 templates (cf9CodeTemplates.xml)

When you do code generation in UML, it will generate ColdFusion stubs. For ORM capabilities, you can add
the "alias" property to create the column="" in the cfproperty created.  This goes the same for the 
alias of the UML class it will translate to the table="" in the cfcomponent tag.