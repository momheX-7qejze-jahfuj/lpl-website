/* ============================================================
   THE LEADERSHIP PRESSURE LAB™ — SHARED JAVASCRIPT
   Copyright © 2026 Joseph "Coach Joe" Clementi
   All rights reserved · coachjoeleadership.com
   ============================================================ */
(function(){
  'use strict';

  /* NAV SCROLL EFFECT */
  const nav = document.querySelector('.nav');
  const backTop = document.querySelector('.back-top');
  const onScroll = () => {
    if (nav) nav.classList.toggle('scrolled', window.scrollY > 40);
    if (backTop) backTop.classList.toggle('visible', window.scrollY > 400);
  };
  window.addEventListener('scroll', onScroll, {passive:true});
  onScroll();

  /* MOBILE MENU */
  const hamburger = document.querySelector('.nav__hamburger');
  const mobileMenu = document.querySelector('.nav__mobile');
  const mobileLinks = document.querySelectorAll('.nav__mobile .nav__link, .nav__mobile .nav__cta');
  if (hamburger && mobileMenu) {
    hamburger.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      hamburger.setAttribute('aria-expanded', open);
      document.body.style.overflow = open ? 'hidden' : '';
    });
    mobileLinks.forEach(l => l.addEventListener('click', () => {
      mobileMenu.classList.remove('open');
      document.body.style.overflow = '';
    }));
  }

  /* REVEAL ON SCROLL */
  const reveals = document.querySelectorAll('.reveal');
  if (reveals.length) {
    const io = new IntersectionObserver((entries) => {
      entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('in-view'); io.unobserve(e.target); }});
    }, {threshold: 0.12, rootMargin: '0px 0px -40px 0px'});
    reveals.forEach(el => io.observe(el));
  }

  /* ACCORDION */
  document.querySelectorAll('.accordion-trigger').forEach(trigger => {
    trigger.addEventListener('click', () => {
      const body = trigger.nextElementSibling;
      const isOpen = body.classList.contains('open');
      document.querySelectorAll('.accordion-body.open').forEach(b => { b.classList.remove('open'); b.previousElementSibling.classList.remove('open'); });
      if (!isOpen) { body.classList.add('open'); trigger.classList.add('open'); }
    });
  });

  /* ACTIVE NAV LINKS */
  const currentPage = window.location.pathname.split('/').pop() || 'index.html';
  document.querySelectorAll('.nav__link').forEach(link => {
    const href = link.getAttribute('href');
    if (href === currentPage || (currentPage === '' && href === 'index.html')) {
      link.classList.add('active');
    }
  });

  /* COOKIE BANNER */
  const cookie = document.querySelector('.cookie-banner');
  if (cookie && !localStorage.getItem('lpl_cookie_consent')) {
    cookie.classList.add('visible');
    cookie.querySelector('.cookie-btn--accept')?.addEventListener('click', () => {
      localStorage.setItem('lpl_cookie_consent', '1');
      cookie.classList.remove('visible');
    });
    cookie.querySelector('.cookie-btn--decline')?.addEventListener('click', () => {
      localStorage.setItem('lpl_cookie_consent', '0');
      cookie.classList.remove('visible');
    });
  }

  /* COUNTER ANIMATION */
  document.querySelectorAll('[data-count]').forEach(el => {
    const io2 = new IntersectionObserver(entries => {
      if (entries[0].isIntersecting) {
        const target = parseInt(el.dataset.count);
        const duration = 1800;
        const step = target / (duration / 16);
        let current = 0;
        const timer = setInterval(() => {
          current = Math.min(current + step, target);
          el.textContent = (el.dataset.prefix || '') + Math.round(current).toLocaleString() + (el.dataset.suffix || '');
          if (current >= target) clearInterval(timer);
        }, 16);
        io2.unobserve(el);
      }
    }, {threshold: 0.5});
    io2.observe(el);
  });

  /* CALENDLY PLACEHOLDER */
  window.openCalendly = function() {
    if (typeof Calendly !== 'undefined') {
      Calendly.initPopupWidget({url: 'https://calendly.com/YOUR-LINK-HERE'});
    } else {
      alert('Calendly not yet configured. Add your Calendly link to js/main.js and the Calendly script to index.html.');
    }
  };


  /* RESOURCES DROPDOWN — close on outside click */
  document.addEventListener('click', (e) => {
    const drop = e.target.closest('.nav__has-drop');
    document.querySelectorAll('.nav__has-drop').forEach(d => {
      if (d !== drop) d.querySelector('.nav__dropdown')?.style.removeProperty('opacity');
    });
  });
  /* Prevent default on dropdown trigger link */
  document.querySelectorAll('.nav__drop-trigger').forEach(t => {
    t.addEventListener('click', e => { e.preventDefault(); });
  });

})();
