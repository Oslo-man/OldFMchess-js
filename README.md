# OldFMchess-js

Play it here: https://oldfmchess-js.vercel.app/

## Tutorial

## Run

Install Node.js first.

Then install http-server:

```bash
npm install -g http-server
```

Run:

```bash
npx http-server
```

Open:

```txt
http://127.0.0.1:8080
```

Or:

```txt
http://192.168.100.35:8080
```
## Credits

Based on GarboChess JS by Gary Linscott.

Further modified and developed by Marcell Wang.

### New features 

- Added tapered evaluation
- Added pawn structure evaluation
- Added 2 strength levels
- Redesigned UI
- Merge material updating with PST values
- Put move scoring inline in generator
- Remove need for fliptable in PST tables. Access them by color
- Optimize pawn move generation
