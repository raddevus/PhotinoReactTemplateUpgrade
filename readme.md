To upgrade your PhotinoReact project template:

1. Create your PhotinoReact project (from old template)
2. Drop all these files (3 files total) into the root of your project directory.
3. package.json & package-lock.json will overwrite the two files in the UserInterface\ directory.
4. run the make.bat from your root project directory and it will :
<pre>
     a) cd to UserInterface
     b) npm run build (rebuild your ReactJS interface)
     c) xcopy files to appropriate directories
     d) cd back to root
     e) start the dotnet project
</pre>
