create a new repository on the command line
echo "# alipayh5test.github.com" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sycamores/alipayh5test.github.com.git
git push -u origin master

push an existing repository from the command line
git remote add origin https://github.com/sycamores/alipayh5test.github.com.git
git push -u origin master

