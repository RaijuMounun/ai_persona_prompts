Ana projede
```
git submodule add https://github.com/RaijuMounun/ai_persona_prompts.git .prompts
git submodule update --init --recursive
```
kullanın. Bu sayede prompts reposundaki güncellemeleri kaçırmazsınız.

```
git submodule update --remote
```
ile değişiklik olursa güncel versiyonu çekebilirsiniz.


---

global.md dosyası global kurallar için oluşturulmuştur. Direkt agentic ide içinden eklenemeyebilir.
Global kuralları tuttuğu .md dosyasını bulup içeriğini onunla değiştirebilirsiniz.

Konuşmaya
"
Bro, load system protocols from @.prompts/global_rules.md. Then, adopt the persona from @.prompts/architect.md. Let's ...
"
şeklinde başlayabilirsiniz.