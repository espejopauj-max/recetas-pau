/**
 * RecetasFáciles.com — main.js
 * UX enhancements, sticky nav, animations, reading progress
 */

document.addEventListener('DOMContentLoaded', () => {

  /* === NAVBAR SCROLL EFFECT === */
  const nav = document.getElementById('mainNav');
  if (nav) {
    window.addEventListener('scroll', () => {
      nav.classList.toggle('scrolled', window.scrollY > 50);
    });
  }

  /* === AOS-LIKE SCROLL ANIMATION (ligero, sin librería) === */
  const animEls = document.querySelectorAll('[data-aos]');
  if (animEls.length) {
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.animationPlayState = 'running';
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });

    animEls.forEach(el => {
      el.style.animationPlayState = 'paused';
      observer.observe(el);
    });
  }

  /* === READING PROGRESS BAR (páginas de receta) === */
  const progressBar = document.getElementById('readingProgress');
  if (progressBar) {
    window.addEventListener('scroll', () => {
      const total = document.body.scrollHeight - window.innerHeight;
      const pct   = total > 0 ? (window.scrollY / total) * 100 : 0;
      progressBar.style.width = pct + '%';
    });
  }

  /* === BACK TO TOP === */
  const topBtn = document.getElementById('backToTop');
  if (topBtn) {
    window.addEventListener('scroll', () => {
      topBtn.classList.toggle('visible', window.scrollY > 400);
    });
    topBtn.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  }

  /* === SMOOTH SCROLL para anchor links === */
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        e.preventDefault();
        const offset = 80;
        window.scrollTo({
          top: target.getBoundingClientRect().top + window.scrollY - offset,
          behavior: 'smooth'
        });
      }
    });
  });

  /* === NEWSLETTER FORM (fake submit para demo) === */
  const newsletterBtn = document.querySelector('.newsletter-box .btn-primary');
  if (newsletterBtn) {
    newsletterBtn.addEventListener('click', () => {
      const input = newsletterBtn.previousElementSibling;
      if (input && input.value.includes('@')) {
        newsletterBtn.innerHTML = '<i class="bi bi-check-circle me-2"></i>¡Suscrito!';
        newsletterBtn.disabled = true;
        newsletterBtn.style.background = '#16a34a';
        input.value = '';
      } else if (input) {
        input.classList.add('is-invalid');
        setTimeout(() => input.classList.remove('is-invalid'), 2000);
      }
    });
  }

  /* === STICKY CTA en receta (aparece al llegar a los pasos) === */
  const stickyCTA = document.getElementById('stickyCTA');
  if (stickyCTA) {
    const trigger = document.getElementById('pasos');
    if (trigger) {
      window.addEventListener('scroll', () => {
        const pos = trigger.getBoundingClientRect().top;
        stickyCTA.classList.toggle('visible', pos < 0);
      });
    }
  }

  /* === PRINT RECIPE === */
  const printBtn = document.getElementById('printRecipe');
  if (printBtn) {
    printBtn.addEventListener('click', () => window.print());
  }

  /* === AD LAZY LOAD SIMULATION (para AdSense real) === */
  // En producción aquí iría el código de AdSense
  const adBlocks = document.querySelectorAll('.ad-block');
  const adObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('ad-loaded');
        adObserver.unobserve(entry.target);
      }
    });
  }, { rootMargin: '100px' });
  adBlocks.forEach(ad => adObserver.observe(ad));

});
