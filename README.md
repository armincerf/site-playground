# site-playground

First get site running using the alx/alexd-site branch

Then install the insite-console
    - Go to site/opt/insite-console and read the README for installation instructions

You should now be able to see a list of apis at http://localhost:5509/_site/insite/app/apis

Now run `ls schema.graphql resources.edn | entr -s './deploy'` to watch the schema and resources files and deploy them when they change. You may need install entr

play with changing the schema and querying it using the console
