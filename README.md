# 📄 연수생 우선명 답안지

---

## 1. 🔗 깃허브 계정(레포지터리) 주소  
🌐 https://github.com/murasakijyuutann/myProfile

---

## 2. 🌍 사이트 도메인 주소  
🚀 https://murasakijyuutann.github.io/myProfile

---

## 3. 🖥️ 디지털 시계 (JavaScript 코드)

```html
<script>
  // ⏰ Select the clock display element
  const display = document.getElementById("display");

  // 🔄 Function to update the clock
  function updateClock() {
    const date = new Date();
    display.textContent = date.toLocaleTimeString();
  }

  // ⚡ Update immediately on page load
  updateClock();

  // ⏳ Keep updating every second
  setInterval(updateClock, 1000);
</script>
```
