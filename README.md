# 1<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>สมัครแข่งแบดมินตัน</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f8fb;
      margin: 0;
      padding: 20px;
    }

    .container {
      max-width: 500px;
      background: white;
      margin: 50px auto;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    h2 {
      text-align: center;
      color: #2d89ef;
    }

    label {
      display: block;
      margin: 15px 0 5px;
    }

    input, select {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    button {
      width: 100%;
      padding: 12px;
      background-color: #2d89ef;
      color: white;
      border: none;
      border-radius: 6px;
      margin-top: 20px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background-color: #1b65c1;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>สมัครแข่งแบดมินตัน</h2>
    <form action="#" method="POST">
      <label for="fullname">ชื่อ-นามสกุล</label>
      <input type="text" id="fullname" name="fullname" required />

      <label for="age">อายุ</label>
      <input type="number" id="age" name="age" min="5" required />

      <label for="gender">เพศ</label>
      <select id="gender" name="gender" required>
        <option value="">-- เลือกเพศ --</option>
        <option value="ชาย">ชาย</option>
        <option value="หญิง">หญิง</option>
        <option value="อื่นๆ">อื่นๆ</option>
      </select>

      <label for="level">ระดับฝีมือ</label>
      <select id="level" name="level" required>
        <option value="">-- เลือกระดับ --</option>
        <option value="มือใหม่">มือใหม่</option>
        <option value="ระดับกลาง">ระดับกลาง</option>
        <option value="ระดับแข่งขัน">ระดับแข่งขัน</option>
      </select>

      <label for="phone">เบอร์โทรศัพท์</label>
      <input type="tel" id="phone" name="phone" required />

      <button type="submit">ส่งใบสมัคร</button>
    </form>
  </div>
</body>
</html>
