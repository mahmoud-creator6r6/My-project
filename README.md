# My-project
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>جدول المعدات والتواصل</title>
  <style>
    /* أضف أي تعديلات على الستايل حسب احتياجاتك */
  </style>
</head>

<body>

  <div class="table-container">
    <!-- جدول المعدات والتعديلات الأخرى -->
  </div>

  <div class="table-container">
    <!-- جدول الموقع الجغرافي والتعديلات الأخرى -->
  </div>

  <div class="contact-info-container">
    <h2>أرقام التواصل</h2>
    <p>للتواصل، يرجى الاتصال على الأرقام التالية:</p>
    <p>الهاتف: +123456789</p>
    <p>البريد الإلكتروني: example@email.com</p>
    
    <!-- زر الاتصال -->
    <button class="action-button" onclick="callPhoneNumber()">اتصل</button>

    <!-- زر فتح الخرائط -->
    <button class="action-button" onclick="openGoogleMaps('موقع بوبكات')">فتح الخرائط</button>
  </div>

  <script>
    function callPhoneNumber() {
      const phoneNumber = '+123456789';
      window.location.href = `tel:${phoneNumber}`;
    }

    function openGoogleMaps(location) {
      const mapsUrl = `https://www.google.com/maps?q=${encodeURIComponent(location)}`;
      window.open(mapsUrl, '_blank');
    }
  </script>

</body>

</html>

