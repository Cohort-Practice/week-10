# making of a database using neondb with a simple node js application

- npm init -y
- npx tsc --init
- npm i pg
- npm i @types/pg
- configure the package.json & tsconfig.json
- "type": "module" --- in package.json
- and this in tsconfig ---
    "module": "nodenext",
    "moduleResolution": "NodeNext"


## run it 
- tsc -b
- node dist/index.js
 **you want to see in neon db** 
- run the command \dt in Sql Editor in neondb