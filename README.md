While in Dev

I'm using the following command to build the source file, and execute it against the test airbnb.js.md file

    cake build && bin/docco --layout codeconv airbnb.js.md && sed "s/docco.css/resources\/codeconv\/docco.css/" < docs/airbnb.js.html > index.html && rm -r docs