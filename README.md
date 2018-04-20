https://github.com/dsolio/test_word_doc.git

…or create a new repository on the command line
echo "# test_word_doc" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/dsolio/test_word_doc.git
git push -u origin master


…or push an existing repository from the command line 
git remote add origin https://github.com/dsolio/test_word_doc.git
git push -u origin master


Steps to version control word document using markdown files:
// convert docx to markdown file
pandoc -s TheBestofRedditin2017.docx -t markdown -o TheBestofRedditin2017.md
// add both the docx and the md file
git add TheBestofRedditin2017.docx TheBestofRedditin2017.md
// commit the changes
git commit -m "ADD COMMENTS HERE"
// push to master
git push -u origin master

