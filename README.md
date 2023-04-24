# Genshin-Impact-AutoTool-Redeem-Codes
I created this utility for myself, but decided to share the creation of such utilities. automated utility for activating promotional codes in genshin impact

You must be sure to specify the information in the config all examples below

```json
{
   "accounts":[
      {
         "automated_codes_enabled":false,
         "name":"account_name",
         "uid":1234567,
         "cookie":"cookie_token_v2=859f4abef1f1df5c6ca496913c6f27f9caf72e3bbe4eed11123fb34492593a8d-kEMPXrzpcB; account_id_v2=415561512",
         "regions":[
            "os_euro"
         ]
      }
   ]
}
```

```automated_codes_enabled``` enabled codes or not for this account

```name: "account_name"``` your_account_name

```uid: 123456``` your in game uid

```cookie: ""``` your cookie token and account id in web

```regions: [ "os_euro" ]``` This program support only one region ```os_euro``` or ```os_asia``` without Arrays

how to get cookies go to the site https://genshin.hoyoverse.com/en/gift
open the developer console write > copy(document.cookie)

after that it is added to your clipboard, paste it either into a file or in the browser ```CTRL + V``` You are looking for the necessary lines that I indicated in the example above and use

# **if the utility is still not published, expect it is still under minor revision and I don't know if it's worth downloading the source code, it's based on the Java language**
