Questo file spiega in che modo Visual Studio ha creato il progetto.

Per generare questo progetto sono stati usati gli strumenti seguenti:
- TypeScript Compiler (tsc)

Per generare questo progetto sono stati eseguiti i passaggi seguenti:
- Creare il file di progetto (`Hanami-Templates.esproj`).
- Creare `launch.json` per abilitare il debug.
- Installare i pacchetti npm e creare `tsconfig.json`: `npm init && npm i --save-dev eslint @types/node typescript && npx tsc --init --sourceMap true`.
- Creare `app.ts`.
- Aggiornare il punto di ingresso `package.json`.
- Aggiornare gli script di compilazione TypeScript in `package.json`.
- Creare `eslint.config.js` per abilitare il linting.
- Aggiungi progetto alla soluzione.
- Scrivere questo file.
