---
icon: fas fa-briefcase
order: 4
---

## Services Offered

<div class="svc-grid">
  <div class="row g-4">
    <div class="col-md-6 col-lg-3">
      <div class="svc-card">
        <div class="svc-icon"><i class="fas fa-wifi"></i></div>
        <h3>Wireless</h3>
        <p>Site surveys, AP deployment, and WLAN troubleshooting to keep your wireless network performing at its best.</p>
      </div>
    </div>
    <div class="col-md-6 col-lg-3">
      <div class="svc-card">
        <div class="svc-icon"><i class="fas fa-network-wired"></i></div>
        <h3>General Network Troubleshooting</h3>
        <p>Layer 1–7 diagnostics and performance analysis to identify and resolve issues across your network stack.</p>
      </div>
    </div>
    <div class="col-md-6 col-lg-3">
      <div class="svc-card">
        <div class="svc-icon"><i class="fas fa-sitemap"></i></div>
        <h3>Network Consultation</h3>
        <p>Architecture design and vendor-neutral advice tailored to your environment and long-term goals.</p>
      </div>
    </div>
    <div class="col-md-6 col-lg-3">
      <div class="svc-card">
        <div class="svc-icon"><i class="fas fa-file-alt"></i></div>
        <h3>Documentation &amp; Diagram Services</h3>
        <p>Topology diagrams, runbooks, and SOPs that give your team clear, accurate references for daily operations.</p>
      </div>
    </div>
  </div>
</div>

---

## Book a Service

<div class="svc-form-section">

  <div id="svc-success-msg" role="alert">
    <i class="fas fa-check-circle"></i>
    <strong>Message received!</strong> Thank you for reaching out — I will be in touch shortly.
  </div>

  <form
    class="svc-form"
    action="https://formsubmit.co/dayrja@gmail.com"
    method="POST"
  >
    <input type="hidden" name="_subject" value="New Service Request — Ayrton Networks">
    <input type="hidden" name="_next" value="https://www.ayrton-networks.com/services/?success=true">
    <input type="hidden" name="_captcha" value="false">
    <input type="text" name="_honey" style="display:none">

    <div class="mb-3">
      <label for="svc-name" class="form-label">Name <span aria-hidden="true">*</span></label>
      <input type="text" id="svc-name" name="name" class="form-control" placeholder="Your full name" required>
    </div>

    <div class="mb-3">
      <label for="svc-phone" class="form-label">Phone</label>
      <input type="tel" id="svc-phone" name="phone" class="form-control" placeholder="Optional">
    </div>

    <div class="mb-3">
      <label for="svc-email" class="form-label">Email <span aria-hidden="true">*</span></label>
      <input type="email" id="svc-email" name="email" class="form-control" placeholder="you@example.com" required>
    </div>

    <div class="mb-3">
      <label for="svc-description" class="form-label">Description <span aria-hidden="true">*</span></label>
      <textarea id="svc-description" name="description" class="form-control" placeholder="Briefly describe what you need..." required></textarea>
    </div>

    <button type="submit" class="svc-submit-btn">Send Request</button>
  </form>

</div>

<script>
  (function () {
    if (window.location.search.indexOf('success=true') !== -1) {
      var msg = document.getElementById('svc-success-msg');
      if (msg) { msg.style.display = 'block'; }
    }
  })();
</script>
