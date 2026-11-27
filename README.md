# local-rust-server

Pocket MCR (Android) için Rust tabanlı Minecraft Java sunucu motorunun derlenmiş sürümleri.

## Atıf ve lisans
Bu motor **Horizon**'dur. Telif: Ludovic Marie ve Horizon katkıcıları. Asıl proje:
https://github.com/horizon-rust/horizon

Bu depo, Android derlemesi için Starling / Horizon Android çalışmasından türetilmiştir:
- https://github.com/starling-client/starling
- https://github.com/Vasysik/horizon-android

Burada yayınlanan sürüm (etiket `ocmr-0.9.0`, kaynak: `v0.9.0`, commit `ff303502a4f7`) **MIT** lisanslıdır.
`LICENSE`, `THIRD_PARTY_NOTICES.md` ve `licenses/` değiştirilmeden korunur. Horizon'un sonraki sürümlerinde
lisans değişmiş olabilir (upstream'de LGPL-3.0-veya-üstü görünüyor); motor sürümü yükseltilirken lisans
yeniden kontrol edilir.

Bu depo, Horizon yazarlarıyla bağlantılı değildir ve onlar tarafından onaylanmamıştır.

## Bu deposunda ne var, ne yok
Android (arm64, musl) için derleme iş akışları ve sürüm dosyaları. **Minecraft oyun dosyası yoktur.**
Oyun dosyaları, kullanıcının cihazında Mojang'ın kendi adreslerinden indirilip hazırlanır.

## Marka
Resmî bir Minecraft ürünü değildir. Mojang veya Microsoft tarafından onaylanmamıştır ve onlarla
bağlantılı değildir. Minecraft, Mojang Studios ve Microsoft'un markasıdır.
