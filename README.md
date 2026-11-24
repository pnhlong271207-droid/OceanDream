<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>OceanDream.vn – Đèn ngủ đại dương</title>
<style>
/* ... phần CSS ... */
</style>
</head>
<body>
<nav><div class="wrap">
  <a href="#top" class="logo">🌊 <span class="grad">OceanDream.vn</span></a>
  <ul><li><a href="#loiich">Lợi ích</a></li><li><a href="#tinhnang">Tính năng</a></li><li><a href="#sanpham">Sản phẩm</a></li><li><a href="#danhgia">Đánh giá</a></li><li><a href="#tracuu">Tra cứu đơn</a></li><li><a href="#trahang">Trả hàng</a></li><li><a href="#faq">FAQ</a></li></ul>
  <div><button class="btn ghost sm" id="adminBtn">⚙ Quản trị</button> <button class="btn ghost sm" id="userBtn" onclick="openAuth()">👤 <span class="hm">Đăng nhập</span></button> <button class="btn sm" id="cartBtn">🛒 Giỏ<span id="cartCount">0</span></button></div>
</div></nav>

<header class="hero" id="top"><div class="wrap">
  <div>
    <h1>Ngủ ngon cùng <span class="grad">ánh sáng đại dương</span></h1>
    <p>Đèn ngủ OceanDream.vn mang sóng biển dịu nhẹ vào phòng bạn – ánh sáng ấm, êm mắt, giúp cả nhà thư giãn và ngủ sâu hơn mỗi đêm.</p>
    <a href="#sanpham" class="btn">Mua ngay</a> <a href="#lienhe" class="btn ghost">Nhận ưu đãi 10%</a>
    <div class="badges"><span>✔ Bảo hành 12 tháng</span><span>✔ Miễn phí đổi trả 7 ngày</span><span>✔ Giao hàng toàn quốc</span></div>
  </div>
  <div class="lamp"><div class="orb"></div><div class="base"></div>
    <i class="bubble" style="width:14px;height:14px;left:18%;bottom:60px"></i><i class="bubble" style="width:22px;height:22px;left:75%;bottom:40px;animation-delay:3s"></i><i class="bubble" style="width:10px;height:10px;left:55%;bottom:70px;animation-delay:6s"></i>
  </div>
</div></header>

<section id="loiich"><div class="wrap reveal">
  <h2>Vì sao chọn <span class="grad">OceanDream.vn</span>?</h2><p class="sub">Dành cho mọi người – từ em bé đến người lớn tuổi</p>
  <div class="grid">
    <div class="glass"><div class="ic">😴</div><h3>Ngủ sâu hơn</h3><p>Ánh sáng ấm, không chói giúp thư giãn và dễ chìm vào giấc ngủ.</p></div>
    <div class="glass"><div class="ic">👁️</div><h3>Dịu mắt</h3><p>Công nghệ LED chống chói, không nhấp nháy, an toàn cho trẻ nhỏ.</p></div>
    <div class="glass"><div class="ic">🏡</div><h3>Đẹp mọi không gian</h3><p>Thiết kế tối giản, hợp phòng ngủ, phòng khách, bàn làm việc.</p></div>
    <div class="glass"><div class="ic">💸</div><h3>Giá hợp lý</h3><p>Chất lượng cao với mức giá dễ tiếp cận cho mọi gia đình.</p></div>
  </div>
  <div class="stats"><div><b class="grad">12.000+</b>khách hàng</div><div><b class="grad">4.9/5</b>đánh giá</div><div><b class="grad">12 tháng</b>bảo hành</div></div>
</div></section>

<section id="tinhnang"><div class="wrap reveal">
  <h2>Tính năng nổi bật</h2><p class="sub">Nhỏ gọn nhưng đầy đủ mọi thứ bạn cần</p>
  <div class="grid">
    <div class="glass"><div class="ic">🎨</div><h3>16 màu & 5 chế độ</h3><p>Chọn màu, độ sáng và hiệu ứng sóng bằng cảm ứng hoặc điều khiển từ xa.</p></div>
    <div class="glass"><div class="ic">⏱️</div><h3>Hẹn giờ tắt</h3><p>Tự tắt sau 30/60/120 phút, tiết kiệm điện.</p></div>
    <div class="glass"><div class="ic">🔋</div><h3>Pin 12 giờ</h3><p>Sạc USB-C, dùng liên tục cả đêm, mang đi dễ dàng.</p></div>
    <div class="glass"><div class="ic">🎵</div><h3>Âm thanh sóng biển</h3><p>Tích hợp loa nhỏ phát tiếng sóng, mưa, gió êm dịu.</p></div>
  </div>
</div></section>

<section id="sanpham"><div class="wrap reveal">
  <h2>Sản phẩm <span class="grad">đặt hàng ngay</span></h2><p class="sub">Thêm vào giỏ và đặt hàng trực tiếp trên trang</p>
  <div class="grid" id="products"></div>
</div></section>

<section id="danhgia"><div class="wrap reveal">
  <h2>Khách hàng nói gì?</h2><p class="sub">Đánh giá thật từ người đã mua</p>
  <div class="two">
    <div class="glass" id="reviews"></div>
    <div class="glass"><h3 style="margin-bottom:12px">Viết đánh giá của bạn</h3>
      <input id="rvName" placeholder="Tên của bạn">
      <select id="rvStar"><option value="5">★★★★★ Tuyệt vời</option><option value="4">★★★★ Tốt</option><option value="3">★★★ Bình thường</option><option value="2">★★ Chưa tốt</option><option value="1">★ Tệ</option></select>
      <textarea id="rvText" rows="4" placeholder="Chia sẻ cảm nhận về sản phẩm..."></textarea>
      <label class="stock" style="display:block;margin-bottom:6px">📷 Ảnh sản phẩm thực tế (tối đa 3 ảnh)</label>
      <input type="file" id="rvFile" accept="image/*" multiple onchange="prevRv(this)"><div class="thumbs" id="rvPrev"></div>
      <button class="btn" onclick="addReview()">Gửi đánh giá</button></div>
  </div>
</div></section>

<section id="tracuu"><div class="wrap reveal">
  <h2>Tra cứu đơn hàng</h2><p class="sub">Nhập mã đơn, mã đơn trên sàn hoặc số điện thoại đã đặt</p>
  <div class="glass" style="max-width:640px;margin:auto">
    <input id="lookQ" placeholder="VD: OD-123456, mã đơn sàn hoặc 09xxxxxxxx">
    <button class="btn" onclick="lookup()">Tra cứu</button><div id="lookRes" style="margin-top:16px"></div>
  </div>
</div></section>

<section id="trahang"><div class="wrap reveal">
  <h2>Yêu cầu <span class="grad">trả hàng</span></h2><p class="sub">Đổi trả trong 7 ngày nếu lỗi nhà sản xuất</p>
  <div class="glass" style="max-width:640px;margin:auto">
    <input id="rtCode" placeholder="Mã đơn hàng (VD: OD-123456)"><input id="rtPhone" placeholder="Số điện thoại đã đặt hàng">
    <select id="rtReason"><option value="">-- Chọn lý do trả hàng --</option><option>Sản phẩm bị lỗi / không hoạt động</option><option>Hư hỏng do vận chuyển</option><option>Giao sai sản phẩm / thiếu phụ kiện</option><option>Không đúng mô tả</option><option>Không còn nhu cầu</option><option>Khác</option></select>
    <textarea id="rtNote" rows="3" placeholder="Mô tả chi tiết (bắt buộc nếu chọn “Khác”)"></textarea>
    <button class="btn" onclick="requestReturn()">Gửi yêu cầu trả hàng</button>
    <p class="stock" style="margin-top:12px">Theo dõi tình trạng yêu cầu tại mục “Tra cứu đơn hàng”.</p>
  </div>
</div></section>

<section id="lienhe" class="cta"><div class="wrap reveal">
  <div class="glass" style="max-width:720px;margin:auto;padding:44px 28px">
    <h2>Nhận <span class="grad">giảm 10%</span> cho đơn đầu tiên</h2><p class="sub">Để lại thông tin, chúng tôi gửi mã ưu đãi và tư vấn miễn phí.</p>
    <input id="ldName" placeholder="Họ và tên"><input id="ldContact" placeholder="Số điện thoại hoặc email">
    <button class="btn" onclick="addLead()">Nhận ưu đãi ngay</button>
  </div>
</div></section>

<section id="faq"><div class="wrap reveal" style="max-width:760px">
  <h2>Câu hỏi thường gặp</h2><p class="sub">&nbsp;</p>
  <div class="glass">
    <details><summary>Đèn có an toàn cho trẻ em không?</summary><p>Có. Chất liệu không độc hại, LED không nhấp nháy, nhiệt độ thấp.</p></details>
    <details><summary>Giao hàng mất bao lâu?</summary><p>2–4 ngày làm việc toàn quốc, nội thành có thể nhận trong ngày.</p></details>
    <details><summary>Chính sách đổi trả?</summary><p>Đổi trả trong 7 ngày nếu lỗi nhà sản xuất, bảo hành 12 tháng. Gửi yêu cầu tại mục “Trả hàng” kèm lý do.</p></details>
    <details><summary>Thanh toán thế nào?</summary><p>Tiền mặt khi nhận hàng (COD) hoặc chuyển khoản bằng cách quét mã QR khi đặt hàng.</p></details>
    <details><summary>Làm sao biết đơn hàng của tôi?</summary><p>Dùng mục “Tra cứu đơn hàng” với mã đơn hoặc số điện thoại.</p></details>
  </div>
</div></section>

<section id="admin"><div class="wrap">
  <h2>Quản trị <span class="grad">OceanDream.vn</span></h2><p class="sub">Doanh thu, lợi nhuận, giá, tồn kho, đơn hàng & lead</p>
  <div class="kpi" id="kpi"></div>
  <div class="glass" style="margin-bottom:20px"><h3 style="margin-bottom:12px">🧾 Nhập đơn hàng đã bán</h3>
    <div class="two"><div>
      <input id="soCode" placeholder="Mã đơn hàng (để trống = tự tạo, VD: OD-123456)"><select id="soPlat"></select><input id="soPlatCode" placeholder="Mã đơn trên sàn (VD: 241124ABCXYZ)"><select id="soPay"></select><input id="soName" placeholder="Tên khách (không bắt buộc)"><input id="soPhone" placeholder="SĐT khách (để khách tra cứu đơn)"><input id="soDate" type="date">
    </div><div>
      <select id="soProd" onchange="soFill()"></select><input id="soQty" type="number" min="1" value="1" placeholder="Số lượng"><input id="soPrice" type="number" min="0" placeholder="Giá bán thực tế / 1 sản phẩm (đ)">
      <label style="font-size:.9rem;color:var(--mut)"><input type="checkbox" id="soStock" checked style="width:auto;margin-right:6px">Trừ số lượng khỏi tồn kho</label>
    </div></div><br><button class="btn" onclick="addSold()">Lưu đơn đã bán</button></div>
  <div class="glass" style="margin-bottom:20px"><h3 style="margin-bottom:12px">➕ Thêm sản phẩm mới</h3>
    <div class="two"><div>
      <input id="npName" placeholder="Tên sản phẩm *"><input id="npDesc" placeholder="Mô tả ngắn">
      <input id="npPrice" type="number" min="0" placeholder="Giá bán (đ) *"><input id="npCost" type="number" min="0" placeholder="Giá nhập (đ)"><input id="npStock" type="number" min="0" placeholder="Số lượng tồn kho *">
    </div><div>
      <input type="file" id="npFile" accept="image/*" onchange="prevNew(this)"><input id="npUrl" placeholder="hoặc dán link ảnh (https://...)" onchange="npImg=this.value.trim();setPrev(npImg)">
      <div class="pimg" id="npPrev" style="height:130px;font-size:1rem;color:var(--mut)">🖼️ Xem trước ảnh</div>
      <button class="btn" onclick="addProd()">Thêm sản phẩm</button>
    </div></div></div>
  <div class="glass" style="margin-bottom:20px"><h3>Danh sách sản phẩm (sửa trực tiếp trong bảng)</h3><div class="tw"><table id="aProd"></table></div></div>
  <div class="glass" style="margin-bottom:20px"><h3>Đơn hàng</h3><div class="tw"><table id="aOrd"></table></div></div>
  <div class="glass" style="margin-bottom:20px"><h3>👥 Tài khoản khách hàng</h3><div class="tw"><table id="aUsers"></table></div></div>
  <div class="glass" style="margin-bottom:20px"><h3>↩ Yêu cầu trả hàng</h3><div class="tw"><table id="aRet"></table></div></div>
  <div class="glass" style="margin-bottom:20px"><h3 style="margin-bottom:12px">💳 Thanh toán chuyển khoản</h3><div class="two"><div>
    <p class="stock" style="margin-bottom:8px">Tải ảnh mã QR ngân hàng/ví để khách quét khi chọn “Chuyển khoản”.</p>
    <input type="file" id="qrFile" accept="image/*" onchange="upQR(this)">
    <textarea id="bankInfo" rows="3" placeholder="Thông tin tài khoản (VD: Vietcombank - 0123456789 - NGUYEN VAN A)" onchange="db.bank=this.value.trim();save();renderQR()"></textarea>
    <button class="btn ghost sm" onclick="db.qr='';save();renderQR();toast('Đã xóa mã QR')">Xóa mã QR</button>
  </div><div id="qrPrev" class="qrbox"></div></div></div>
  <div class="glass"><h3>Danh sách lead</h3><div class="tw"><table id="aLead"></table></div></div>
  <div class="glass" style="margin-top:20px;max-width:520px"><h3 style="margin-bottom:12px">🔑 Đổi mã PIN quản trị</h3>
    <input id="pinOld" type="password" inputmode="numeric" placeholder="PIN hiện tại"><input id="pinNew" type="password" inputmode="numeric" placeholder="PIN mới (4–8 chữ số)"><input id="pinNew2" type="password" inputmode="numeric" placeholder="Nhập lại PIN mới">
    <button class="btn" onclick="changePin()">Đổi mã PIN</button></div>
</div></section>

<footer>© 2026 OceanDream.vn · Hotline 0853 542 726 · Dữ liệu lưu trên trình duyệt này</footer>

<aside class="drawer" id="drawer">
  <div class="row"><h3>🛒 Giỏ hàng</h3><button class="btn ghost sm" onclick="toggleCart()">Đóng</button></div>
  <div id="cartItems"></div>
  <h3 style="margin:14px 0">Tổng: <span id="cartTotal" class="price">0đ</span></h3>
  <input id="coName" placeholder="Họ và tên"><input id="coPhone" placeholder="Số điện thoại"><input id="coAddr" placeholder="Địa chỉ nhận hàng">
  <h3 style="margin:6px 0">Hình thức thanh toán</h3>
  <div class="pay" onchange="payChg()">
    <label class="on"><input type="radio" name="pay" value="Thanh toán khi giao hàng" checked> 🚚 Thanh toán khi giao hàng (COD)</label>
    <label><input type="radio" name="pay" value="Tiền mặt"> 💵 Tiền mặt (trả trực tiếp tại shop)</label>
    <label><input type="radio" name="pay" value="Chuyển khoản"> 🏦 Chuyển khoản (quét mã QR)</label>
  </div>
  <div class="qrbox" id="qrBox" style="display:none"></div>
  <button class="btn" onclick="checkout()" style="width:100%">Đặt hàng</button>
</aside>
<div class="modal" id="authModal" onclick="if(event.target===this)closeAuth()"><div class="glass mbox"><div class="row" style="margin:0 0 14px"><h3 id="authTitle"></h3><button class="btn ghost sm" onclick="closeAuth()">✕</button></div><div id="authBody"></div></div></div>
<div class="lb" id="lb" onclick="this.classList.remove('open')"><img id="lbImg" alt=""></div>
<div class="toast" id="toast"></div>

<script>
/* ... phần JavaScript ... */
</script>
</body>
</html>
