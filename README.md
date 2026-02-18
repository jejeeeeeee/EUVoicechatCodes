# EUVoicechatCodes

## Template

Your codes file must be written in **JSON format**, not Lua. Roblox cannot decode Lua tables from GitHub.

Example template:

```json
{
  "CodeName": {
    "ExpireTime": 1767225600,
    "Rewards": {
      "Auras": "AuraName",
      "Minutes": 10,
      "Tokens": 10,
      "Title": "TitelName"
    }
  }
}
```

## Explanation

**CodeName**
The name of the code players will redeem

**ExpireTime**
Must be a Unix timestamp (seconds since Jan 1, 1970 UTC)
Use https://www.unixtimestamp.com to generate one

**Rewards**
Fields:

* `Auras` — string
* `Minutes` — number
* `Tokens` — number
* `Title` — string

## Important Notes

* Do NOT use `return {}`
* Do NOT use comments inside JSON
* File must be valid JSON
