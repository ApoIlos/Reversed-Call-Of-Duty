# Reversing call of duty.

I made this repo to help and educate people on reverse engineering games(Ie. Call of duty),   
Addresses, Patterns(Sigs), Class's will be posted here as well as gudes on how to find them.

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/ApoIlos)  

![Profile views](https://gpvc.arturio.dev/ApoIlos)  

## Info
* Addresses(Offsets by some) are pointers in memory we can use them to call game functions, Or read a piece of text, int, bools.
* Patterns(Sigs) are a row of bytes mostly used to help update Addresses when there's a game update, we can also scan patterns to remove the need of hard-coding addresses.
* Class's store data like health, armour, ammo, stats, server info, clients, jus about anything.

## Tools
* IDA(PRO) Is used to reverse the game. You can get it here > https://www.hex-rays.com/products/ida/
* x64dbg/x86dbg's Scylla is used to dump the game so we can load it in ida, x64dbg/x86dbg can also be used to reverse the game(Its also free) but its downside is its missing alot of features handy for reverses.

## Languages
Q: What programming languages to use?         
A: Well it depends on your skill level but most used one is c++.

* Use c++ for hooking game functions.

## Hooks
* Minhook is a awesome hooking library for c++ https://github.com/TsudaKageyu/minhook

## Injectors
I mostly use Xenos as its simple and safe for most games(I will not provide a dl link).

## End info
Ik this readme is not great but i will be updating it over time.
