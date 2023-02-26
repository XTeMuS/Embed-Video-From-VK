# Embed-Video-From-VK
Embed Video From VK

ไม่มีอะไรมากแค่เอาไว้เป็นความรู้ กลัวลืม ตามหัวข้อเลย

วิธีการทำ
คลิกขวาที่คลิป แล้วเลือก คัดลอกรหัสวิดีโอ(Copy embed code) เอาลิงค์ไปใส่ iframe ได้เลย

เพิ่มเติม ตัวแปร ตามชื่อตัวแปรก็บอกคือ HD หรือไม่ และ Autoplay ชื่อก็บอกอยู่แล้ว ตามนั้นเลย
&hd=1
&autoplay=1

ข้างล่างนี้โค้ดจาก codepen


<div class="video-container"><iframe width="853" height="480" src="https://vk.com/video_ext.php?oid=-116782009&id=456239250&hash=4fa87c0d3d44c087&hd=1&autoplay=1" frameborder="0" allowfullscreen</iframe</div>

<style type="text/css">
.video-container {
position: relative;
padding-bottom: 56.25%;
padding-top: 30px; height: 0; overflow: hidden;
}

.video-container iframe,
.video-container object,
.video-container embed {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
}
</style>


จบเพียงเท่านี้ นำไปใช้งานได้เลย ใน VK คลิปเยอะเต็มไปหมด
