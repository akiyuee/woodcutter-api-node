## woodcutter-api-node
Simple API endpoint that simulates Woodcutters' autistic and cuckery braincells.  

### How to use?  
The API is publicly accessible at `Soon™`. The response will be returned in JSON type.

### Usage example
*Assuming you use Axios in NodeJS*  
```js
axios.get('SOON/api?input=query').then(function (response) {
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

### Available queries  
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

### Contributing
You can help me contribute to the response database by submitting phrases in array-type.
