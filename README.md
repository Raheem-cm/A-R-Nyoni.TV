#  # A-R-Nyoni.TV 📺

> Android App ya kuangalia **live streams** kupitia [AppCreator24](https://www.appcreator24.com).  
> Inaunganisha vipindi vya habari, sayansi, muziki na sehemu za majadiliano kwa urahisi.

---

## 🎬 Sections Ndani ya App
1. **Live News (Al Jazeera Mubasher)**  
   🔗 [HLS Stream](https://live-hls-web-ajm.getaj.net/AJM/index.m3u8)  

2. **NASA Live**  
   🔗 [YouTube Stream](https://www.youtube.com/embed/live_stream?channel=UCLA_DiR1FfKNvjuUpBHmylQ)  

3. **Lofi Girl 24/7 (Music)**  
   🔗 [YouTube Stream](https://www.youtube.com/watch?v=jfKfPfyJRdk)  

4. **Chat Room**  
   💬 Watumiaji wanaweza kuchat, kushare picha na video, na kufanya video call.  

5. **Forum**  
   📌 Makundi ya majadiliano: `News`, `Music`, `Space`

---

## 🛠 Jinsi ya Kuunda App kwa AppCreator24
1. Ingia [AppCreator24](https://www.appcreator24.com).
2. Bonyeza **Create new app** → weka jina **A-R-Nyoni.TV**.
3. Ongeza sections kwa kutumia faili **`appcreator24_payload.json`**.
4. Hifadhi na shusha **APK**.
5. Binafsisha zaidi:
   - 🖼️ Badilisha icon (tumia `assets/icon.png` au tengeneza yako)
   - 🎨 Badilisha theme (dark, light, rangi tofauti)
   - 🔔 Ongeza push notifications
   - 💰 Ongeza ads kwa monetization

---

## ⚡ Mfano wa kutumia API kwa `curl`
```bash
curl -X POST "https://www.appcreator24.com" \
  -H "Content-Type: application/x-www-form-urlencoded" \
  --data-binary "@appcreator24_payload.json"
