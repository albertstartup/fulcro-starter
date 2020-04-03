# fulcro-starter

Fulcro starter kit derived from the Fulcro [book](http://book.fulcrologic.com/) 

## Usage

1. Start the Fulcro server to manage builds, note this does not
automatically start any builds

   ```sh
   npx shadow-cljs server
   ```
      
2. Navigate to the localhost address logged by shadow and start
the desired build and navigate to the app address, `localhost:8000`

3. Start the `SHADOW REPL` run configuration

4. Once connected to the nREPL, select the build you want to work
against

   ```shell script
   (shadow/repl :main)
   ```    

