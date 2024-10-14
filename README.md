# Uppgift 23
Mystiska tecken spökar i vår fil. Vad kan detta bero på?

## Problemet
Givetvis är det specificeringen  US-ASCII i metacharset som ställer till det. Det innebär att enbart tecken som ingår i det engelska alfabetet kan tolkas rätt av webbläsaren.
## Lösningen
Om vi istället använder ex UTF-8 så får vi istället korrekt resultat. En annan lösning är att hårdkoda å, ä och ö med hjälp av ascii koder. Det tar massa tid, men det går: &aring ; blir: &aring; 