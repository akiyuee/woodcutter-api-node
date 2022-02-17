# <img src="https://cdn.discordapp.com/emojis/932559342065049641.png?size=28" alt="."/> woodcutter-api-node
Simple API endpoint that simulates Woodcutters' autistic and cuckery braincells. 

### <img src="https://cdn.discordapp.com/emojis/943154284135079946.png?size=28" alt="."/> How to use?  
The API is publicly accessible at `https://woodcutter-api-node.herokuapp.com`. Endpoint: `/api?input=YOUR_QUERY_HERE`.  
Responses will be returned in JSON format.

### Realized by:
<table>
    <tr>
      <td align="center"><a href="https://nodejs.org/"><img src="https://cdn.discordapp.com/emojis/932559343600156674.png" width="64" height="64" alt="."/><br/><sub><b>NodeJS</b></sub></a><br/></td>
      <td align="center"><a href="https://heroku.com/"><img src="https://brand.heroku.com/static/media/heroku-logo-stroke.aa0b53be.svg" width="64" height="64" alt="."/><br/><sub><b>Heroku</b></sub></a><br/></td>
    </tr>
</table>

### <img src="https://cdn.discordapp.com/emojis/932559343600156674.png?size=20" alt="."/> Usage example
*Assuming you use Axios in NodeJS:*  
```js
axios.get('https://woodcutter-api-node.herokuapp.com/api?input=query').then(function (response) {
    // handle success
    console.log(response.data);
    //
    // {
    //    response: 'beluga là vua của discord content tất cả mọi content discord đều ăn cắp ý tưởng beluga không xin phép',
    //    id: 'llLtjyznql4AIUH'
    // }
    // 
}).catch(function (error) {
    // handle error
    console.log('error');
})
```

### <img src="https://cdn.discordapp.com/emojis/943101872548511775.png?size=20" alt="."/> Available queries  
> I recommend you to use the `retard` query, since it is **the most frequently-updated array**.  

| ID | Name | Description |
| ------------- | ------------- | ------------ |
| 1 | `smp` | Minecraft survival-multiplayer related phrases. |
| 2 | `genz` | Facebook humour related phrases / words |
| 3 | `hungg` | I mean, *why not.* |
| 4 | `dream` | Ah yes, my favorite Content Creator that has a fandom full of autism and retardness. |
| 5 | `retard` | Generic autistic responses. |
| 6 | `underage` | Kids are kids, retards are retards, 2k10 are 2k10, no exception. |
| 7 | `hololive` | Hololive-related retard phrases from Vietnamese "fans", or should I say "kiddies that watched Game Cục Cứt." |
| 8 | `rickcringe` | Imagine spamming a song from 1987 and still think it's funny. It is funny as how your brain malfunctions like a germ died from hand sanitizer. |
| 9 | `belucringe` | "Beluga is the creator of Discord-related content on Youtube" - Some woodcutter, probably. |

### <img src="https://cdn.discordapp.com/emojis/943157377874665473.png?size=20" alt="."/> Contributing
You can help me contribute to the response database by submitting phrases in array-type.  


---
<p align="center">Made with ❤️ by Enderman.</p>
