<!DOCTYPE html>
<!-- saved from url=(0025)https://www.google.co.jp/ -->
<html itemscope="" itemtype="http://schema.org/WebPage" lang="ja">

<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<meta content="origin" name="referrer">
	<meta content="/images/branding/googleg/1x/googleg_standard_color_128dp.png" itemprop="image">
	<title>Google</title>
	<script src="./いんでっくす_files/cb=gapi.loaded_0" nonce="" async=""></script>
	<script nonce="">
	(function() {
		var _g = {
			kEI: 'KnDAZtO4CObk2roP-pvLiAs',
			kEXPI: '31',
			kBL: 'GSl2',
			kOPI: 89978449
		};
		(function() {
			var a;
			((a = window.google) == null ? 0 : a.stvsc) ? google.kEI = _g.kEI: window.google =
				_g;
		}).call(this);
	})();
	(function() {
		google.sn = 'webhp';
		google.kHL = 'ja';
	})();
	(function() {
		var h = this || self;

		function l() {
			return window.google !== void 0 && window.google.kOPI !== void 0 && window.google
				.kOPI !== 0 ? window.google.kOPI : null
		};
		var m, n = [];

		function p(a) {
			for (var b; a && (!a.getAttribute || !(b = a.getAttribute("eid")));) a = a.parentNode;
			return b || m
		}

		function q(a) {
			for (var b = null; a && (!a.getAttribute || !(b = a.getAttribute("leid")));)
				a = a.parentNode;
			return b
		}

		function r(a) {
			/^http:/i.test(a) && window.location.protocol === "https:" && (google.ml &&
				google.ml(Error("a"), !1, {
					src: a,
					glmm: 1
				}), a = "");
			return a
		}

		function t(a, b, c, d, k) {
			var e = "";
			b.search("&ei=") === -1 && (e = "&ei=" + p(d), b.search("&lei=") === -1 &&
				(d = q(d)) && (e += "&lei=" + d));
			d = "";
			var g = b.search("&cshid=") === -1 && a !== "slh",
				f = [];
			f.push(["zx", Date.now().toString()]);
			h._cshid && g && f.push(["cshid", h._cshid]);
			c = c();
			c != null && f.push(["opi", c.toString()]);
			for (c = 0; c < f.length; c++) {
				if (c === 0 || c > 0) d += "&";
				d += f[c][0] + "=" + f[c][1]
			}
			return "/" + (k || "gen_204") + "?atyp=i&ct=" + String(a) + "&cad=" + (b +
				e + d)
		};
		m = google.kEI;
		google.getEI = p;
		google.getLEI = q;
		google.ml = function() {
			return null
		};
		google.log = function(a, b, c, d, k, e) {
			e = e === void 0 ? l : e;
			c || (c = t(a, b, e, d, k));
			if (c = r(c)) {
				a = new Image;
				var g = n.length;
				n[g] = a;
				a.onerror = a.onload = a.onabort = function() {
					delete n[g]
				};
				a.src = c
			}
		};
		google.logUrl = function(a, b) {
			b = b === void 0 ? l : b;
			return t("", a, b)
		};
	}).call(this);
	(function() {
		google.y = {};
		google.sy = [];
		var d;
		(d = google).x || (d.x = function(a, b) {
			if (a) var c = a.id;
			else {
				do c = Math.random(); while (google.y[c])
			}
			google.y[c] = [a, b];
			return !1
		});
		var e;
		(e = google).sx || (e.sx = function(a) {
			google.sy.push(a)
		});
		google.lm = [];
		var f;
		(f = google).plm || (f.plm = function(a) {
			google.lm.push.apply(google.lm, a)
		});
		google.lq = [];
		var g;
		(g = google).load || (g.load = function(a, b, c) {
			google.lq.push([
				[a], b, c
			])
		});
		var h;
		(h = google).loadAll || (h.loadAll = function(a, b) {
			google.lq.push([a, b])
		});
		google.bx = !1;
		var k;
		(k = google).lx || (k.lx = function() {});
		var l = [],
			m;
		(m = google).fce || (m.fce = function(a, b, c, n) {
			l.push([a, b, c, n])
		});
		google.qce = l;
	}).call(this);
	google.f = {};
	(function() {
		document.documentElement.addEventListener("submit", function(b) {
			var a;
			if (a = b.target) {
				var c = a.getAttribute("data-submitfalse");
				a = c === "1" || c === "q" && !a.elements.q.value ? !0 : !1
			} else a = !1;
			a && (b.preventDefault(), b.stopPropagation())
		}, !0);
		document.documentElement.addEventListener("click", function(b) {
			var a;
			a: {
				for (a = b.target; a && a !== document.documentElement; a = a.parentElement)
					if (a.tagName === "A") {
						a = a.getAttribute("data-nohref") === "1";
						break a
					}
				a = !1
			}
			a && b.preventDefault()
		}, !0);
	}).call(this);
	(function() {
		google.hs = {
			h: true,
			nhs: false,
			sie: false
		};
	})();
	(function() {
		google.c = {
			btfi: false,
			c4t: false,
			caf: false,
			cap: 2000,
			cfr: false,
			cli: false,
			crp: false,
			csp: false,
			csxs: false,
			di: false,
			doiu: 0,
			fla: false,
			fli: false,
			gl: true,
			irsf: false,
			lhc: false,
			marb: true,
			mcc: false,
			pci: true,
			raf: false,
			taf: true,
			timl: false,
			tprc: false,
			vis: true,
			wh0: false,
			whu: false
		};
	})();
	(function() {
		var p = this || self;
		window.google = window.google || {};
		var r = window.performance && window.performance.timing && "navigationStart" in
			window.performance.timing,
			aa = google.stvsc && google.stvsc.ns,
			t = r ? aa || window.performance.timing.navigationStart : void 0;

		function u() {
			return window.performance.now() - (google.stvsc && google.stvsc.pno || 0)
		}
		var ba = google.stvsc && google.stvsc.rs,
			v = r ? ba || window.performance.timing.responseStart : void 0;

		function ca(a, b, c) {
			a: {
				for (var d = a; d && d !== b; d = d.parentElement)
					if (d.style.overflow === "hidden" || d.tagName === "G-EXPANDABLE-CONTENT" &&
						getComputedStyle(d).getPropertyValue("overflow") === "hidden") {
						b = d;
						break a
					}
				b = null
			}
			if (!b) return !1;a = c(a);c = c(b);
			return a.bottom < c.top || a.top >= c.bottom || a.right < c.left || a.left >=
				c.right
		}

		function da(a) {
			return a.style.display === "none" ? !0 : document.defaultView && document.defaultView
				.getComputedStyle ? (a = document.defaultView.getComputedStyle(a), !!a &&
					(a.visibility === "hidden" || a.height === "0px" && a.width === "0px")) :
				!1
		}

		function ea(a, b, c, d, e) {
			var h = e(a),
				k = h.left + (c ? 0 : window.pageXOffset),
				m = h.top + (c ? 0 : window.pageYOffset),
				n = h.width,
				f = h.height,
				g = 0;
			if (!b && f <= 0 && n <= 0) return g;
			b = window.innerHeight || document.documentElement.clientHeight;
			m + f < 0 ? g = 2 : m >= b && (g = 4);
			if (k + n < 0 || k >= (window.innerWidth || document.documentElement.clientWidth))
				g |= 8;
			else if (d) {
				k = h.left;
				if (!c)
					for (; a && a !== d; a = a.parentElement) k += a.scrollLeft;
				d = e(d);
				if (k + n < d.left || k >= d.right) g |= 8;
				h.top >= d.bottom && (g |= 4)
			}
			g || (g = 1, m + f > b && (g |= 4));
			return g
		};
		var fa = google.c.cap,
			ha = google.c.csp,
			ia = google.c.cli,
			ja = google.c.doiu,
			w = google.c.vis,
			x = google.c.gl,
			ka = google.c.marb,
			la = google.c.taf,
			ma = google.c.wh0,
			y = google.c.timl,
			na = google.c.whu,
			oa = google.c.pci;

		function z(a, b) {
			google.tick("load", a, b)
		}

		function A(a, b) {
			google.c.e("load", a, String(b))
		}

		function B(a, b, c, d) {
			a.addEventListener ? a.addEventListener(b, c, d || !1) : a.attachEvent && a
				.attachEvent("on" + b, c)
		}

		function C(a, b, c, d) {
			"addEventListener" in a ? a.removeEventListener(b, c, d || !1) : a.attachEvent &&
				a.detachEvent("on" + b, c)
		};
		var pa = function(a, b, c) {
				this.g = a;
				this.v = [];
				this.B = this.g.hasAttribute("data-noaft");
				this.j = !!this.g.getAttribute("data-deferred");
				var d;
				if (d = !this.j) a: {
					for (d = 0; d < D.length; ++d)
						if (a.getAttribute("data-" + D[d])) {
							d = !0;
							break a
						}
					d = !1
				}
				this.l = d;
				this.F = this.g.hasAttribute("data-bsrc");
				(a = this.g.src) && this.l && (this.D = a);
				!this.l && typeof a === "string" && a || this.g.setAttribute("data-lzy_",
					"1");
				this.B ? b = !0 : b || x && this.i || this.j || this.l ? b = !1 : (b =
					this.g.src, b = typeof b !== "string" || !b, a = this.g.getAttribute(
						"data-cmp"), b =
					a !== null ? a === "1" : b || this.g.complete);
				this.A = b;
				x || this.A || this.i || E(this);
				w && !c && F(this)
			},
			E = function(a) {
				google.rll(a.g, !0, function() {
					G(a, Date.now())
				})
			},
			F = function(a) {
				if (a.C === void 0) {
					var b = a.g;
					var c;
					a: {
						for (c = b; c; c = c.parentElement)
							if (c.tagName === "G-SCROLLING-CAROUSEL" || ha && c.classList.contains(
									"XNfAUb")) break a;
						c = null
					}
					var d = b.parentElement;
					if (d && (d.tagName === "G-IMG" || d.classList.contains("uhHOwf")) && (d.style
							.height || d.style.width)) {
						var e = d.getBoundingClientRect(),
							h = b.getBoundingClientRect();
						if (ia) {
							if (e.height <
								h.height || e.width < h.width) b = d
						} else if (e.height <= h.height || e.width <= h.width) b = d
					}
					b = google.cv(b, !1, void 0, c);
					a.C = b
				}
				return a.C
			},
			G = function(a, b) {
				if (a.D && a.g.src === a.D || a.g.getAttribute("data-deferred") === "1") x ||
					E(a);
				else if (!a.i) {
					a.j && a.g.setAttribute("data-deferred", "3");
					a.i = b;
					b = a.i;
					for (var c = 0; c < a.v.length; ++c) a.v[c](b, a.g);
					a.v.length = 0
				}
			},
			D = "src bsrc url ll image img-url lioi".split(" ");
		google.c.iim = google.c.iim || {};
		var H = google.c.iim,
			qa = 0;

		function I(a, b, c, d) {
			var e = a.getAttribute("data-csiid");
			e || (e = String(++qa), oa && (e = google.kEI + "_" + e));
			H[e] || (a.setAttribute("data-csiid", e), H[e] = b ? b(a) : new pa(a, c, d));
			return H[e]
		}

		function J(a) {
			for (var b = document.getElementsByTagName("img"), c = 0, d = b.length; c <
				d; ++c) a(I(b[c]))
		};

		function ra(a) {
			if (a && (a = a.target, a.tagName === "IMG")) {
				var b = Date.now();
				G(I(a, void 0, !0, !0), b)
			}
		}

		function K(a) {
			google.c.oil(a)
		};
		google.timers = {};
		google.startTick = function(a) {
			google.timers[a] = {
				t: {
					start: Date.now()
				},
				e: {},
				m: {}
			}
		};
		google.tick = function(a, b, c) {
			google.timers[a] || google.startTick(a);
			c = c !== void 0 ? c : Date.now();
			b instanceof Array || (b = [b]);
			for (var d = 0, e; e = b[d++];) google.timers[a].t[e] = c
		};
		google.c.e = function(a, b, c) {
			google.timers[a].e[b] = c
		};
		google.c.b = function(a, b) {
			b = google.timers[b || "load"].m;
			b[a] && google.ml(Error("a"), !1, {
				m: a
			});
			b[a] = !0
		};
		google.c.u = function(a, b) {
			var c = google.timers[b || "load"];
			b = c.m;
			if (b[a]) {
				b[a] = !1;
				for (a in b)
					if (b[a]) return !1;
				x && (C(document.documentElement, "load", K, !0), C(document.documentElement,
					"error", K, !0));
				google.csiReport(c, "all");
				return !0
			}
			c = "";
			for (var d in b) c += d + ":" + b[d] + ";";
			google.ml(Error("b"), !1, {
				m: a,
				b: b[a] === !1,
				s: c
			});
			return !1
		};
		google.rll = function(a, b, c) {
			function d(e) {
				c(e);
				C(a, "load", d);
				C(a, "error", d)
			}
			B(a, "load", d);
			b && B(a, "error", d)
		};
		p.google.aft = function(a) {
			a.setAttribute("data-iml", String(Date.now()))
		};
		google.startTick("load");
		google.tick("load", "hst", window._hst);
		var L = google.timers.load;
		if (!google.stvsc || google.stvsc.sw) {
			var M = L.t,
				N = window.performance;
			N && (t && v && v > t && v <= M.start ? (M.start = v, L.wsrt = v - t) : N.now &&
				(L.wsrt = Math.floor(u())))
		}
		google.c.b("xe", "load");
		!window._hst && performance && performance.mark && performance.mark(
			"SearchHeadStart");
		var O;
		if ((O = google.stvsc) == null ? 0 : O.start) google.timers.load.t.start =
			google.stvsc.start;

		function P(a) {
			if (document.visibilityState === "hidden") {
				google.c.fh = a;
				var b;
				t && (b = Math.floor(t + a));
				google.tick("load", "fht", b);
				return !0
			}
			return !1
		}

		function Q(a) {
			P(a.timeStamp) && C(document, "visibilitychange", Q, !0)
		}
		google.c.fh = Infinity;
		B(document, "visibilitychange", Q, !0);
		P(0);
		x && (google.c.oil = ra, B(document.documentElement, "load", K, !0), B(
			document.documentElement, "error", K, !0));
		google.cv = function(a, b, c, d) {
			if (!a || !b && da(a)) return 0;
			if (!a.getBoundingClientRect) return 1;
			var e = function(h) {
				return h.getBoundingClientRect()
			};
			return !b && ca(a, d, e) ? 0 : ea(a, b, c, d, e)
		};

		function R(a) {
			try {
				a()
			} catch (b) {
				google.ml(b, !1)
			}
		}

		function sa() {
			if (google.aftq !== null) {
				google.tick("load", "aftqf", Date.now());
				for (var a, b = 0, c; c = (a = google.aftq) == null ? void 0 : a[b++];) R(
					c);
				google.aftq = null
			}
		}
		google.caft = function(a) {
			google.aftq === null ? R(a) : (google.aftq = google.aftq || [], google.aftq
				.push(a))
		};

		function S() {
			return window.performance && window.performance.navigation && window.performance
				.navigation.type
		};
		var ta = window.location,
			ua = "aft afti aftr afts cbs cbt fht frts frvt hct hst prt prs sct".split(
				" ");

		function T(a) {
			return (a = ta.search.match(new RegExp("[?&]" + a + "=(\\d+)"))) ? Number(a[
				1]) : -1
		}

		function U(a) {
			var b = google.timers.load,
				c = b.m;
			if (!c || !c.prs) {
				c = window._csc === "agsa" && window._cshid;
				var d = S() || c ? 0 : T("qsubts");
				d > 0 && (c = T("fbts"), c > 0 && (b.t.start = Math.max(d, c)));
				var e = b.t,
					h = e.start;
				c = {};
				b.wsrt !== void 0 && (c.wsrt = b.wsrt);
				if (h)
					for (var k = 0, m; m = ua[k++];) {
						var n = e[m];
						n && (c[m] = Math.max(n - h, 0))
					}
				d > 0 && (c.gsasrt = b.t.start - d);
				b = b.e;
				a = "/gen_204?s=" + google.sn + "&t=" + a + "&atyp=csi&ei=" + google.kEI +
					"&rt=";
				d = "";
				for (var f in c) a += "" + d + f + "." + c[f], d = ",";
				for (var g in b) a += "&" + g + "=" + b[g];
				f = a;
				g = "";
				a = [];
				p._cshid &&
					a.push(["cshid", p._cshid]);
				b = window.google !== void 0 && window.google.kOPI !== void 0 && window.google
					.kOPI !== 0 ? window.google.kOPI : null;
				b != null && a.push(["opi", b.toString()]);
				for (b = 0; b < a.length; b++) {
					if (b === 0 || b > 0) g += "&";
					g += a[b][0] + "=" + a[b][1]
				}
				a = f + g;
				(f = google.stvsc) && (a += "&ssr=1");
				if (f ? f.isBF : S() === 2) a += "&bb=1";
				S() === 1 && (a += "&r=1");
				"gsasrt" in c && (c = T("qsd"), c > 0 && (a += "&qsd=" + c));
				c = a;
				typeof navigator.sendBeacon === "function" ? navigator.sendBeacon(c, "") :
					google.log("", "", c)
			}
		};

		function V(a) {
			a && google.tick("load", "cbs", a);
			google.tick("load", "cbt");
			U("cap")
		};
		var wa = function(a) {
				var b = va;
				b.g = a;
				b.g && (b.g(), b.g = null)
			},
			va = new function() {
				this.g = null
			};

		function xa(a, b, c) {
			function d() {
				h || k !== m || c(f, n, g)
			}

			function e(l, q) {
				l = Math.max(f, l);
				f !== l && (n = f, g = q);
				f = l;
				++m;
				d()
			}
			var h = !0,
				k = 0,
				m = 0,
				n = 0,
				f = 0,
				g;
			J(function(l) {
				a(l) && (++k, l.i || l.A ? e(l.i || 0, l.g) : l.v.push(e))
			});
			b();
			h = !1;
			d()
		};
		var W = window.performance;

		function ya() {
			if (google.c.c4t && W && W.mark && W.timing) {
				var a = google.timers.load,
					b = a.wsrt;
				a = a.t.aft;
				b && b > 0 && a && a > 0 && (a -= W.timing.navigationStart, a > 0 && (W.mark(
					"SearchAFTStart", {
						startTime: b
					}), W.mark("trigger:SearchAFTEnd", {
					startTime: a
				})))
			}
		};
		var za = !1,
			X = 0,
			Y = 0,
			Z;

		function Aa(a, b) {
			na && !google.c.wh && (google.c.wh = Math.floor(window.innerHeight ||
				document.documentElement.clientHeight), google.c.wh && A("whu", "1"));
			var c = google.c.wh,
				d = !b;
			b = b ? Math.floor(b.getBoundingClientRect().top + window.pageYOffset) : -1;
			var e = ma && !c ? !1 : b >= c;
			Y || !d && !e || (Y = a, X = b);
			if (Y) {
				var h = 0,
					k = 0,
					m = 0,
					n = !1;
				xa(function(f) {
					if (!(F(f) & 1)) return !1;
					if (f.A) return ++m, !f.B;
					F(f) & 4 && (n = !0);
					f.j && ++k;
					++h;
					return !0
				}, function() {
					A("ima", h);
					A("imad", k);
					A("imac", m);
					document.getElementsByClassName("Ib7Efc").length && A("ddl", 1);
					A("wh", c)
				}, function(f, g, l) {
					f && z("afti", f);
					g && z("aftip", g);
					X > 0 && z("afts", Y);
					if (l) {
						var q;
						g = ((q = l.closest("[data-ved]")) == null ? void 0 : q.getAttribute(
							"data-ved")) || "NF";
						A("aftie", g)
					}
					q = Y;
					g = X;
					if (0 > q || ka && c && X < c && 0 >= c) g = q = 0;
					f && (!la || f > q || n) && (q = f, g = c);
					z("aft", q);
					A("aft", 1);
					A("aftp", g);
					wa(function() {
						Z && clearTimeout(Z);
						U("aft")
					});
					ya();
					document.visibilityState === "hidden" && A("hddn", 1);
					google.c.u("aft");
					sa()
				})
			}
		};
		var Ba = !1;

		function Ca(a) {
			a = I(a);
			return x && w || ja !== 0 ? F(a) : 0
		};
		google.c.wh = Math.floor(window.innerHeight || document.documentElement.clientHeight);
		google.c.b("prt");
		var Da = fa || 0;
		if (Da > 0) a: {
			if (t !== void 0) {
				var Ea = u(),
					Fa = Da - Ea;
				if (Fa > 0) {
					Z = setTimeout(V, Fa, Math.floor(t + Ea));
					break a
				}
				V()
			}
			Z = void 0
		}
		google.c.maft = function(a, b) {
			x || J(function() {});
			za || (google.c.b("aft"), za = !0);
			Y || Aa(a, b)
		};
		google.c.miml = function(a) {
			function b(d) {
				var e = F(d);
				d.g.setAttribute("data-atf", String(e));
				return y && !d.B && (!d.l || d.F || !!(F(d) & 1))
			}

			function c(d) {
				y && z("iml", d || a);
				google.c.u("iml")
			}
			Ba || (google.c.b("iml"), function() {
				xa(b, function() {}, c)
			}(0), Ba = !0)
		};
		google.c.ub = function() {};
		if (!x || w) google.c.setup = Ca;
	}).call(this);
	(function() {
		function b() {
			for (var a = google.drc.shift(); a;) a(), a = google.drc.shift()
		};
		google.drc = [function() {
			google.tick && google.tick("load", "dcl")
		}];
		google.dclc = function(a) {
			google.drc.length ? google.drc.push(a) : a()
		};
		window.addEventListener ? (document.addEventListener("DOMContentLoaded", b, !
				1), window.addEventListener("load", b, !1)) : window.attachEvent && window
			.attachEvent("onload", b);
	}).call(this);
	(function() {
		var b = [];
		google.jsc = {
			xx: b,
			x: function(a) {
				b.push(a)
			},
			mm: [],
			m: function(a) {
				google.jsc.mm.length || (google.jsc.mm = a)
			}
		};
	}).call(this);
	(function() {
		var f = function(a) {
				var b = 0;
				return function() {
					return b < a.length ? {
						done: !1,
						value: a[b++]
					} : {
						done: !0
					}
				}
			},
			h = typeof Object.defineProperties == "function" ? Object.defineProperty :
			function(a, b, c) {
				if (a == Array.prototype || a == Object.prototype) return a;
				a[b] = c.value;
				return a
			},
			k = function(a) {
				a = ["object" == typeof globalThis && globalThis, a, "object" == typeof window &&
					window, "object" == typeof self && self, "object" == typeof global &&
					global
				];
				for (var b = 0; b < a.length; ++b) {
					var c = a[b];
					if (c && c.Math == Math) return c
				}
				throw Error("a");
			},
			l = k(this),
			m = function(a, b) {
				if (b) a: {
					var c = l;
					a = a.split(".");
					for (var d = 0; d < a.length - 1; d++) {
						var e = a[d];
						if (!(e in c)) break a;
						c = c[e]
					}
					a = a[a.length - 1];
					d = c[a];
					b = b(d);
					b != d && b != null && h(c, a, {
						configurable: !0,
						writable: !0,
						value: b
					})
				}
			},
			n = function(a) {
				if (!(a instanceof Array)) {
					var b = typeof Symbol != "undefined" && Symbol.iterator && a[Symbol.iterator];
					if (b) a = b.call(a);
					else if (typeof a.length == "number") a = {
						next: f(a)
					};
					else throw Error("b`" + String(a));
					for (var c = []; !(b = a.next()).done;) c.push(b.value);
					a = c
				}
				return a
			},
			p = typeof Object.assign ==
			"function" ? Object.assign : function(a, b) {
				for (var c = 1; c < arguments.length; c++) {
					var d = arguments[c];
					if (d)
						for (var e in d) Object.prototype.hasOwnProperty.call(d, e) && (a[e] = d[
							e])
				}
				return a
			};
		m("Object.assign", function(a) {
			return a || p
		});
		var r = this || self;
		var t =
			"click focusin focusout auxclick change copy dblclick beforeinput input keyup keydown keypress mousedown mouseenter mouseleave mouseout mouseover mouseup paste pointerdown pointerenter pointerleave pointerup touchstart touchmove touchend touchcancel transitioncancel transitionend transitionrun transitionstart dragover dragenter dragleave drop dragstart dragend speech"
			.split(" ").concat(["focus", "blur", "error", "load"]);
		var u = ["focus", "blur", "error", "load", "toggle"];

		function v(a) {
			return a === "mouseenter" ? "mouseover" : a === "mouseleave" ? "mouseout" :
				a === "pointerenter" ? "pointerover" : a === "pointerleave" ? "pointerout" :
				a
		};
		var x = function() {
			var a = w;
			this.v = {};
			this.A = {};
			this.j = null;
			this.g = [];
			this.i = a
		};
		x.prototype.handleEvent = function(a, b, c) {
			y(this, {
				eventType: a,
				event: b,
				targetElement: b.target,
				eic: c,
				timeStamp: Date.now(),
				eia: void 0,
				eirp: void 0,
				eiack: void 0
			})
		};
		var y = function(a, b) {
			if (a.j) a.j(b);
			else {
				b.eirp = !0;
				var c;
				(c = a.g) == null || c.push(b)
			}
		};
		x.prototype.addEvent = function(a, b) {
			var c = this;
			if (!(a in this.v) && this.i) {
				var d = function(g, q, T) {
					c.handleEvent(g, q, T)
				};
				this.v[a] = d;
				b = v(b || a);
				if (b !== a) {
					var e = this.A[b] || [];
					e.push(a);
					this.A[b] = e
				}
				this.i.addEventListener(b, function(g) {
					return function(q) {
						d(a, q, g)
					}
				})
			}
		};
		x.prototype.s = function(a) {
			return this.v[a]
		};
		x.prototype.l = function() {
			this.i.l();
			this.i = null;
			this.v = {};
			this.A = {};
			this.j = null;
			this.g = []
		};
		x.prototype.ecrd = function(a) {
			this.j = a;
			var b;
			if ((b = this.g) == null ? 0 : b.length) {
				for (a = 0; a < this.g.length; a++) y(this, this.g[a]);
				this.g = null
			}
		};
		var z = typeof navigator !== "undefined" && /iPhone|iPad|iPod/.test(
				navigator.userAgent),
			B = function() {
				this.g = A;
				this.i = []
			};
		B.prototype.addEventListener = function(a, b) {
			z && (this.g.style.cursor = "pointer");
			var c = this.i,
				d = c.push,
				e = this.g;
			b = b(this.g);
			var g = !1;
			u.indexOf(a) >= 0 && (g = !0);
			e.addEventListener(a, b, g);
			d.call(c, {
				eventType: a,
				s: b,
				capture: g
			})
		};
		B.prototype.l = function() {
			for (var a = 0; a < this.i.length; a++) {
				var b = this.g,
					c = this.i[a];
				b.removeEventListener ? b.removeEventListener(c.eventType, c.s, c.capture) :
					b.detachEvent && b.detachEvent("on" + c.eventType, c.s)
			}
			this.i = []
		};
		var C = function() {
			this.g = [];
			this.i = [];
			this.j = []
		};
		C.prototype.addEventListener = function(a, b) {
			for (var c = function(e) {
					e.addEventListener(a, b)
				}, d = 0; d < this.g.length; d++) c(this.g[d]);
			this.j.push(c)
		};
		C.prototype.l = function() {
			for (var a = [].concat(n(this.g), n(this.i)), b = 0; b < a.length; b++) a[
				b].l();
			this.g = [];
			this.i = [];
			this.j = []
		};
		var E = function(a) {
			for (var b = D, c = 0; c < b.j.length; c++) b.j[c](a)
		};

		function F(a) {
			for (var b = G, c = 0; c < b.length; ++c)
				if (H(b[c].g, a.g)) return !0;
			return !1
		}

		function H(a, b) {
			if (a === b) return !1;
			for (; a !== b && b.parentNode;) b = b.parentNode;
			return a === b
		};
		var w = new C;
		a: {
			for (var D = w, A = window.document.documentElement, I = 0; I < D.g.length; I++)
				if (A === D.g[I].g) break a;
			var J = new B,
				K;
			b: {
				for (var L = 0; L < D.g.length; L++)
					if (H(D.g[L].g, J.g)) {
						K = !0;
						break b
					}
				K = !1
			}
			if (K) D.i.push(J);
			else {
				E(J);
				D.g.push(J);
				for (var G = [].concat(n(D.i), n(D.g)), M = [], N = [], O = 0; O < D.g.length; ++
					O) {
					var P = D.g[O];
					F(P) ? (M.push(P), P.l()) : N.push(P)
				}
				for (var Q = 0; Q < D.i.length; ++Q) {
					var R = D.i[Q];
					F(R) ? M.push(R) : (N.push(R), E(R))
				}
				D.g = N;
				D.i = M
			}
		}
		for (var S = new x, U = 0; U < t.length; U++) S.addEvent(t[U]);
		(function(a) {
			google.jsad = function(b) {
				b(a)
			}
		})(S);
		var V = Object.assign({}, function(a) {
			return {
				trigger: function(b) {
					var c = a.s(b.type);
					c || (a.addEvent(b.type), c = a.s(b.type));
					var d = b.target || b.srcElement;
					c && c(b.type, b, d.ownerDocument.documentElement)
				},
				configure: function(b) {
					b(a)
				}
			}
		}(S), {
			addEvent: function(a) {
				S.addEvent(a)
			}
		});
		r.gws_wizbind = V;
		(function(a, b) {
			var c = function(d) {
				var e = d.detail;
				e && e._type && b({
					type: e._type,
					target: d.target,
					bubbles: !0,
					detail: e
				})
			};
			a.addEventListener("_custom", c);
			return function() {
				a.removeEventListener("_custom", c)
			}
		})(window.document.documentElement, V.trigger);
	}).call(this);
	(function() {
		function b(c) {
			var a;
			a: {
				for (a = c.target; a && a !== document.documentElement; a = a.parentElement)
					if (a.tagName === "A" && a.getAttribute("data-jsarwt") === "1") break a;
				a = null
			}
			a && window.jsarwt(a, null, c);
			return !0
		};
		window.document.documentElement.addEventListener("mousedown", b, !0);
		window.document.documentElement.addEventListener("touchstart", b, !0);
	}).call(this);

	</script>
	<script nonce="">
	(function() {
		google.xjs = {
			basecomb: '/xjs/_/js/k=xjs.hd.en.EK8zn8JtnBk.O/ck=xjs.hd.8d6sGhq7_SY.L.W.O/am=AIwCAAAAAAAAAMAAAAAAAAAAAAAAAAAAAAAgAAAQAAAAAAAAQArQnQQAKABgAwQAAABAAIAAQIAgAABoAAAAAQIcAFAQAAUIRARABCBIEIBHmQAgBCBMAAEIUBAgAQEgiEIEAADAAABABIABhgEItQAwCBAAAAAAEEAEAABgAGsMIEAAgD4CARwAhAgAACHQAQgAAACAAkCAgAACDJABBAAAAgAAANADgOABOEhhAQAAAAAAAAAAAACAACYI5kICCgIgAAAAAAAAAAAAAAAAAFLSxIUN/d=1/ed=1/dg=0/ujg=1/rs=ACT90oGA-vp-hXG97hk8T-N5REwVoNxJ4Q',
			basecss: '/xjs/_/ss/k=xjs.hd.8d6sGhq7_SY.L.W.O/am=AIwCAAAAAAAAAMAAAAAAAAAAAAAAAAAAAAAgAAAQAAAAAAAAAAqAnQQACABgAwQAAABAAIAAAAAAAABoAAAAAAIYAAAAAAQIQARABAAIEAAAAAAgBCAAAAEIUBAgAQEgiEIAAADAAABABIABhgEItQAwCBAAAAAAEEAEAAAAAGsEIEAAgD4CARwAhAgAACHQAQgAAAAAAkAAAAACDJABBAAAAAAAAAADAAAAAAAAAAAAAAAAAAAAAAAAAAIIAAIACgAAAAAAAAAAAAAAAAAAAEA/rs=ACT90oHlNxtUT4_n1epZKNfke5puVDTQWQ',
			basejs: '/xjs/_/js/k=xjs.hd.en.EK8zn8JtnBk.O/am=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAQAhQAAAAKAAAAAAAAAAAAAAAQIAgAABoAAAAAQAcAFAQAAEABAQAACBAEIBHmQAABABMAAAAABAAAAEgAAAEAADAAAAABAAAAAAANAAAAAAAAAAAAAAAAABgAAEIAAAAAAAAAAAAgAAAAADQAQAAAACAAACAgAAADJABBAAAAgAAANADgOABOEhhAQAAAAAAAAAAAACAACYI5kICCgIgAAAAAAAAAAAAAAAAAFLSxIUN/dg=0/rs=ACT90oFRubqzsddknb-SC2S6vQ59M6Bv0g',
			excm: []
		};
	})();

	</script>
	<script nonce="">
	(function() {
		var f = "src href async nonce type charset crossorigin onload rel".split(" ");
		window._rtf = function(b, c) {
			var a = document.createElement(b.tagName);
			f.forEach(function(e) {
				a[e] = b[e]
			});
			a.onerror = function() {
				window._rtf(a, c)
			};
			var d = b.dataset.rtc === void 0 ? 0 : Number(b.dataset.rtc);
			d >= 4 ? c && c() : (a.dataset.rtc = String(d + 1), setTimeout(function() {
				document.body.appendChild(a)
			}, 50 * Math.pow(2, d) + Math.random() * 50))
		};
	}).call(this);

	</script>
	<link href="./いんでっくす_files/m=cdos,cr,hsm,jsa,mb4ZUb,d,csi,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl"
	onerror="_rtf(this)" rel="stylesheet" nonce="">
	<script nonce="">
	(function() {
		google.kEXPI =
			'0,3700334,615,432,6,91,16,1,544874,72489,217969,50403,64701,58629,20589,42852,6924,159601,5265788,8837026,26,12,14,7440796,19266000,1288236,25238879,87723,52108,53228,22891,18869,10275,588,20694,3061,11591,13526,6136,1668,97,12069,7517,2640,3821,1679,1947,1853,3501,11440,1818,62,153,2955,2472,1476,3602,3914,634,3319,578,2486,5224,40,3866,1121,2130,2198,1704,7003,3402,11,1967,2718,896,778,16,177,1428,2695,560,323,3371,542,339,397,3174,2740,116,545,407,334,1140,39,511,203,510,2746,576,78,576,70,290,523,172,1530,1291,21518293';
	})();
	window._ = window._ || {};
	window._DumpException = _._DumpException = function(e) {
		throw e;
	};
	window._s = window._s || {};
	_s._DumpException = _._DumpException;
	window._qs = window._qs || {};
	_qs._DumpException = _._DumpException;
	(function() {
		var t = [175104, 0, 201326592, 0, 0, 0, 0, 67108872, 0, 687865856, 4840720,
			402721280, 67175427, 65792, 402915336, 436207752, 17440832, 134246408,
			693371269, 268505346, 273166372, 40181248, 33571648, 37765139, 153096304,
			169902087, 277104724, 268435504, 100761604, 47456262, 16814848, 136314880,
			134496272, 738304001, 67240134, 9412608, 67116033, 67108898, 8461570,
			805339136, 8405250, 3147778, 16409, 128, 249856, 551552898, 5652, 0, 0,
			469893120, 607019138, 134251136, 0, 0, 0, 882147328, 886244
		];
		window._F_toggles = window._xjs_toggles = t;
	})();
	window._F_installCss = window._F_installCss || function(css) {};
	(function() {
		window.google.xjsu =
			'/xjs/_/js/k=xjs.hd.en.EK8zn8JtnBk.O/am=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAQAhQAAAAKAAAAAAAAAAAAAAAQIAgAABoAAAAAQAcAFAQAAEABAQAACBAEIBHmQAABABMAAAAABAAAAEgAAAEAADAAAAABAAAAAAANAAAAAAAAAAAAAAAAABgAAEIAAAAAAAAAAAAgAAAAADQAQAAAACAAACAgAAADJABBAAAAgAAANADgOABOEhhAQAAAAAAAAAAAACAACYI5kICCgIgAAAAAAAAAAAAAAAAAFLSxIUN/d=1/ed=1/dg=3/rs=ACT90oFRubqzsddknb-SC2S6vQ59M6Bv0g/ee=ALeJib:B8gLwd;AfeaP:TkrAjf;BMxAGc:E5bFse;BgS6mb:fidj5d;BjwMce:cXX2Wb;CxXAWb:YyRLvc;DM55c:imLrKe;DULqB:RKfG5c;Dkk6ge:wJqrrd;DpcR3d:zL72xf;EABSZ:MXZt9d;ESrPQc:mNTJvc;EVNhjf:pw70Gc;EmZ2Bf:zr1jrb;EnlcNd:WeHg4;Erl4fe:FloWmf,FloWmf;F9mqte:UoRcbe;Fmv9Nc:O1Tzwc;G0KhTb:LIaoZ;G6wU6e:hPyGBb;GleZL:J1A7Od;HMDDWe:G8QUdb;HoYVKb:PkDN7e;HqeXPd:cmbnH;IBADCc:RYquRb;IZrNqe:P8ha2c;IoGlCf:b5lhvb;IsdWVc:qzxzOb;JXS8fb:Qj0suc;JbMT3:M25sS;JsbNhc:Xd8iUd;KOxcK:OZqGte;KQzWid:ZMKkN;KcokUb:KiuZBf;KpRAue:Tia57b;LBgRLc:SdcwHb,XVMNvd;LEikZe:byfTOb,lsjVmc;LXA8b:q7OdKd;LsNahb:ucGLNb;Me32dd:MEeYgc;NPKaK:SdcwHb;NSEoX:lazG7b;Np8Qkd:Dpx6qc;Nyt6ic:jn2sGd;OgagBe:cNTe0;Oj465e:KG2eXe,KG2eXe;OohIYe:mpEAQb;Pjplud:EEDORb,PoEs9b;Q1Ow7b:x5CSu;Q6C5kf:pfdZCe;QGR0gd:Mlhmy;R2kc8b:ALJqWb;R4IIIb:QWfeKf;R9Ulx:CR7Ufe;RDNBlf:zPRCJb;SLtqO:Kh1xYe;SMDL4c:fTfGO,fTfGO;SNUn3:ZwDk9d,x8cHvb;ShpF6e:N0pvGc;SzQQ3e:dNhofb;TxfV6d:YORN0b;U96pRd:FsR04;UBKJZ:LGDJGb;UDrY1c:eps46d;UVmjEd:EesRsb;UyG7Kb:wQd0G;V2HTTe:RolTY;VGRfx:VFqbr;VN6jIc:ddQyuf;VOcgDe:YquhTb;VsAqSb:PGf2Re;VxQ32b:k0XsBb;WCEKNd:I46Hvd;WDGyFe:jcVOxd;Wfmdue:g3MJlb;XUezZ:sa7lqb;YV5bee:IvPZ6d;YkQtAf:rx8ur;ZMvdv:PHFPjb;ZSH6tc:QAvyLe;ZWEUA:afR4Cf;a56pNe:JEfCwb;aAJE9c:WHW6Ef;aCJ9tf:qKftvc;aZ61od:arTwJ;af0EJf:ghinId;bDXwRe:UsyOtc;bcPXSc:gSZLJb;cEt90b:ws9Tlc;cFTWae:gT8qnd;coJ8e:KvoW8;dIoSBb:ZgGg9b;dLlj2:Qqt3Gf;daB6be:lMxGPd;dtl0hd:lLQWFe;eBAeSb:Ck63tb;eBZ5Nd:audvde;eHDfl:ofjVkb;eO3lse:nFClrf;euOXY:OZjbQ;g8nkx:U4MzKc;gaub4:TN6bMe;gtVSi:ekUOYd;h3MYod:cEt90b;hK67qb:QWEO5b;heHB1:sFczq;hjRo6e:F62sG;hsLsYc:Vl118;iFQyKf:QIhFr,vfuNJf;imqimf:jKGL2e;io8t5d:sgY6Zb;jY0zg:Q6tNgc;k2Qxcb:XY51pe;kCQyJ:ueyPK;kMFpHd:OTA3Ae;kbAm9d:MkHyGd;lkq0A:JyBE3e;nAFL3:NTMZac,s39S4;nJw4Gd:dPFZH;oGtAuc:sOXFj;oSUNyd:fTfGO,fTfGO;oUlnpc:RagDlc;okUaUd:wItadb;pKJiXd:VCenhc;pNsl2d:j9Yuyc;pXdRYb:JKoKVe;pj82le:mg5CW;qZx2Fc:j0xrE;qaS3gd:yiLg6e;qavrXe:zQzcXe;qddgKe:d7YSfd,x4FYXe;rQSrae:C6D5Fc;sP4Vbe:VwDzFe;sTsDMc:kHVSUb;sZmdvc:rdGEfc;tH4IIe:Ymry6;tosKvd:ZCqP3;trZL0b:qY8PFe;uY49fb:COQbmf;uuQkY:u2V3ud;vGrMZ:lPJJ0c;vfVwPd:lcrkwe;w3bZCb:ZPGaIb;w4rSdf:XKiZ9;w9w86d:dt4g2b;wQlYve:aLUfP;wR5FRb:O1Gjze,TtcOte;wV5Pjc:L8KGxe;whEZac:F4AmNb;xBbsrc:NEW1Qc;ysNiMc:CpIBjd;yxTchf:KUM7Z;z97YGf:oug9te;zOsCQe:Ko78Df;zaIgPb:Qtpxbd/m=cdos,cr,hsm,jsa,mb4ZUb,d,csi,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl';
		window._F_jsUrl =
			'/xjs/_/js/k=xjs.hd.en.EK8zn8JtnBk.O/am=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAQAhQAAAAKAAAAAAAAAAAAAAAQIAgAABoAAAAAQAcAFAQAAEABAQAACBAEIBHmQAABABMAAAAABAAAAEgAAAEAADAAAAABAAAAAAANAAAAAAAAAAAAAAAAABgAAEIAAAAAAAAAAAAgAAAAADQAQAAAACAAACAgAAADJABBAAAAgAAANADgOABOEhhAQAAAAAAAAAAAACAACYI5kICCgIgAAAAAAAAAAAAAAAAAFLSxIUN/d=1/ed=1/dg=3/rs=ACT90oFRubqzsddknb-SC2S6vQ59M6Bv0g/ee=ALeJib:B8gLwd;AfeaP:TkrAjf;BMxAGc:E5bFse;BgS6mb:fidj5d;BjwMce:cXX2Wb;CxXAWb:YyRLvc;DM55c:imLrKe;DULqB:RKfG5c;Dkk6ge:wJqrrd;DpcR3d:zL72xf;EABSZ:MXZt9d;ESrPQc:mNTJvc;EVNhjf:pw70Gc;EmZ2Bf:zr1jrb;EnlcNd:WeHg4;Erl4fe:FloWmf,FloWmf;F9mqte:UoRcbe;Fmv9Nc:O1Tzwc;G0KhTb:LIaoZ;G6wU6e:hPyGBb;GleZL:J1A7Od;HMDDWe:G8QUdb;HoYVKb:PkDN7e;HqeXPd:cmbnH;IBADCc:RYquRb;IZrNqe:P8ha2c;IoGlCf:b5lhvb;IsdWVc:qzxzOb;JXS8fb:Qj0suc;JbMT3:M25sS;JsbNhc:Xd8iUd;KOxcK:OZqGte;KQzWid:ZMKkN;KcokUb:KiuZBf;KpRAue:Tia57b;LBgRLc:SdcwHb,XVMNvd;LEikZe:byfTOb,lsjVmc;LXA8b:q7OdKd;LsNahb:ucGLNb;Me32dd:MEeYgc;NPKaK:SdcwHb;NSEoX:lazG7b;Np8Qkd:Dpx6qc;Nyt6ic:jn2sGd;OgagBe:cNTe0;Oj465e:KG2eXe,KG2eXe;OohIYe:mpEAQb;Pjplud:EEDORb,PoEs9b;Q1Ow7b:x5CSu;Q6C5kf:pfdZCe;QGR0gd:Mlhmy;R2kc8b:ALJqWb;R4IIIb:QWfeKf;R9Ulx:CR7Ufe;RDNBlf:zPRCJb;SLtqO:Kh1xYe;SMDL4c:fTfGO,fTfGO;SNUn3:ZwDk9d,x8cHvb;ShpF6e:N0pvGc;SzQQ3e:dNhofb;TxfV6d:YORN0b;U96pRd:FsR04;UBKJZ:LGDJGb;UDrY1c:eps46d;UVmjEd:EesRsb;UyG7Kb:wQd0G;V2HTTe:RolTY;VGRfx:VFqbr;VN6jIc:ddQyuf;VOcgDe:YquhTb;VsAqSb:PGf2Re;VxQ32b:k0XsBb;WCEKNd:I46Hvd;WDGyFe:jcVOxd;Wfmdue:g3MJlb;XUezZ:sa7lqb;YV5bee:IvPZ6d;YkQtAf:rx8ur;ZMvdv:PHFPjb;ZSH6tc:QAvyLe;ZWEUA:afR4Cf;a56pNe:JEfCwb;aAJE9c:WHW6Ef;aCJ9tf:qKftvc;aZ61od:arTwJ;af0EJf:ghinId;bDXwRe:UsyOtc;bcPXSc:gSZLJb;cEt90b:ws9Tlc;cFTWae:gT8qnd;coJ8e:KvoW8;dIoSBb:ZgGg9b;dLlj2:Qqt3Gf;daB6be:lMxGPd;dtl0hd:lLQWFe;eBAeSb:Ck63tb;eBZ5Nd:audvde;eHDfl:ofjVkb;eO3lse:nFClrf;euOXY:OZjbQ;g8nkx:U4MzKc;gaub4:TN6bMe;gtVSi:ekUOYd;h3MYod:cEt90b;hK67qb:QWEO5b;heHB1:sFczq;hjRo6e:F62sG;hsLsYc:Vl118;iFQyKf:QIhFr,vfuNJf;imqimf:jKGL2e;io8t5d:sgY6Zb;jY0zg:Q6tNgc;k2Qxcb:XY51pe;kCQyJ:ueyPK;kMFpHd:OTA3Ae;kbAm9d:MkHyGd;lkq0A:JyBE3e;nAFL3:NTMZac,s39S4;nJw4Gd:dPFZH;oGtAuc:sOXFj;oSUNyd:fTfGO,fTfGO;oUlnpc:RagDlc;okUaUd:wItadb;pKJiXd:VCenhc;pNsl2d:j9Yuyc;pXdRYb:JKoKVe;pj82le:mg5CW;qZx2Fc:j0xrE;qaS3gd:yiLg6e;qavrXe:zQzcXe;qddgKe:d7YSfd,x4FYXe;rQSrae:C6D5Fc;sP4Vbe:VwDzFe;sTsDMc:kHVSUb;sZmdvc:rdGEfc;tH4IIe:Ymry6;tosKvd:ZCqP3;trZL0b:qY8PFe;uY49fb:COQbmf;uuQkY:u2V3ud;vGrMZ:lPJJ0c;vfVwPd:lcrkwe;w3bZCb:ZPGaIb;w4rSdf:XKiZ9;w9w86d:dt4g2b;wQlYve:aLUfP;wR5FRb:O1Gjze,TtcOte;wV5Pjc:L8KGxe;whEZac:F4AmNb;xBbsrc:NEW1Qc;ysNiMc:CpIBjd;yxTchf:KUM7Z;z97YGf:oug9te;zOsCQe:Ko78Df;zaIgPb:Qtpxbd/m=cdos,cr,hsm,jsa,mb4ZUb,d,csi,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl';
	})();

	</script>
	<script defer="" src="./いんでっくす_files/m=cdos,cr,hsm,jsa,mb4ZUb,d,csi,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl(1)"
	nonce=""></script>
	<script nonce="">
	(function() {
		window.rwt = function() {
			return !0
		};
	}).call(this);
	(function() {
		var b = this || self;
		var d, e;
		a: {
			for (var f = ["CLOSURE_FLAGS"], g = b, h = 0; h < f.length; h++)
				if (g = g[f[h]], g == null) {
					e = null;
					break a
				}
			e = g
		}
		var k = e && e[610401301];
		d = k != null ? k : !1;
		var l, m = b.navigator;
		l = m ? m.userAgentData || null : null;

		function n(c) {
			return d ? l ? l.brands.some(function(a) {
				return (a = a.brand) && a.indexOf(c) != -1
			}) : !1 : !1
		}

		function t(c) {
			var a;
			a: {
				if (a = b.navigator)
					if (a = a.userAgent) break a;
				a = ""
			}
			return a.indexOf(c) != -1
		};

		function u() {
			return d ? !!l && l.brands.length > 0 : !1
		}

		function v() {
			return t("Safari") && !(w() || (u() ? 0 : t("Coast")) || (u() ? 0 : t(
					"Opera")) || (u() ? 0 : t("Edge")) || (u() ? n("Microsoft Edge") : t(
					"Edg/")) || (u() ? n("Opera") : t("OPR")) || t("Firefox") || t("FxiOS") ||
				t("Silk") || t("Android"))
		}

		function w() {
			return u() ? n("Chromium") : (t("Chrome") || t("CriOS")) && !(u() ? 0 : t(
				"Edge")) || t("Silk")
		};
		var x = function(c) {
			return String(c).replace(/\-([a-z])/g, function(a, p) {
				return p.toUpperCase()
			})
		};
		var z = u() ? !1 : t("Trident") || t("MSIE");
		!t("Android") || w();
		w();
		v();
		var A = !z && !v();
		window.jsarwt = function(c, a, p) {
			if (!a)
				if (A && c.dataset) a = c.dataset;
				else {
					a = {};
					for (var y = c.attributes, q = 0; q < y.length; ++q) {
						var r = y[q];
						if (r.name.lastIndexOf("data-", 0) == 0) {
							var B = x(r.name.slice(5));
							a[B] = r.value
						}
					}
				}
			if (!("jrwt" in a))
				if (window.rwt(c, a.cd || "", a.usg || "", "", a.ved || "", Number(a.au) ||
						null, a.psig || "", p), A && c.dataset) c.dataset.jrwt = "1";
				else {
					if (/-[a-z]/.test("jrwt")) throw Error("a");
					c.setAttribute.call(c, "data-" + "jrwt".replace(/([A-Z])/g, "-$1").toLowerCase(),
						"1")
				}
			return !1
		};
	}).call(this);
	(function() {
		window.google.erd = {
			jsr: 1,
			bv: 2064,
			sd: true,
			de: true
		};
	})();
	(function() {
		var sdo = false;
		var mei = 10;
		var g = this || self;
		var k, l = (k = g.mei) != null ? k : 1,
			n, p = (n = g.sdo) != null ? n : !0,
			q = 0,
			r, t = google.erd,
			v = t.jsr;
		google.ml = function(a, b, d, m, e) {
			e = e === void 0 ? 2 : e;
			b && (r = a && a.message);
			d === void 0 && (d = {});
			d.cad = "ple_" + google.ple + ".aple_" + google.aple;
			if (google.dl) return google.dl(a, e, d, !0), null;
			b = d;
			if (v < 0) {
				window.console && console.error(a, b);
				if (v === -2) throw a;
				b = !1
			} else b = !a || !a.message || a.message === "Error loading script" || q >=
				l && !m ? !1 : !0;
			if (!b) return null;
			q++;
			d = d || {};
			b = encodeURIComponent;
			var c = "/gen_204?atyp=i&ei=" + b(google.kEI);
			google.kEXPI && (c += "&jexpid=" + b(google.kEXPI));
			c += "&srcpg=" + b(google.sn) + "&jsr=" + b(t.jsr) +
				"&bver=" + b(t.bv);
			t.dpf && (c += "&dpf=" + b(t.dpf));
			var f = a.lineNumber;
			f !== void 0 && (c += "&line=" + f);
			var h = a.fileName;
			h && (h.indexOf("-extension:/") > 0 && (e = 3), c += "&script=" + b(h), f &&
				h === window.location.href && (f = document.documentElement.outerHTML.split(
					"\n")[f], c += "&cad=" + b(f ? f.substring(0, 300) :
					"No script found.")));
			google.ple && google.ple === 1 && (e = 2);
			c += "&jsel=" + e;
			for (var u in d) c += "&", c += b(u), c += "=", c += b(d[u]);
			c = c + "&emsg=" + b(a.name + ": " + a.message);
			c = c + "&jsst=" + b(a.stack || "N/A");
			c.length >= 12288 && (c = c.substr(0, 12288));
			a = c;
			m || google.log(0, "", a);
			return a
		};
		window.onerror = function(a, b, d, m, e) {
			r !== a && (a = e instanceof Error ? e : Error(a), d === void 0 ||
				"lineNumber" in a || (a.lineNumber = d), b === void 0 || "fileName" in a ||
				(a.fileName = b), google.ml(a, !1, void 0, !1, a.name === "SyntaxError" ||
					a.message.substring(0, 11) === "SyntaxError" || a.message.indexOf(
						"Script error") !== -1 ? 3 : 0));
			r = null;
			p && q >= l && (window.onerror = null)
		};
	})();;
	this.gbar_ = {
		CONFIG: [
			[
				[0, "www.gstatic.com", "og.qtm.en_US.KZAWJ1ProoE.2019.O", "co.jp", "ja",
					"538", 0, [4, 2, "", "", "", "662508795", "0"], null,
					"KnDAZqHTCbu50-kPgvC2MA", null, 0, "og.qtm.mfypcKMzPvw.L.W.O",
					"AA2YrTv0taM5qVgw38gU_15kX9WFXe5TPw",
					"AA2YrTsXU5hjdOZrxXehYcpWx5cYm18ejw", "", 2, 1, 200, "JPN", null, null,
					"1", "538", 1, null, null, 89978449, 1
				], null, [1, 0.1000000014901161, 2, 1], null, [0, 0, 0, null, "", "", "",
					"", 0, 0, 0, ""
				],
				[0, 0, "", 1, 0, 0, 0, 0, 0, 0, null, 0, 0, null, 0, 0, null, null, 0, 0,
					0, "", "", "", "", "", "", null, 0, 0, 0, 0, 0, null, null, null,
					"rgba(32,33,36,1)", "rgba(255,255,255,1)", 0, 0, 1, null, null, null, 0,
					null, null, 0
				], null, null, ["1", "gci_91f30755d6a6b787dcc2a4062e6e9824.js",
					"googleapis.client:gapi.iframes", "", "ja"
				], null, null, null, null, [
					"m;/_/scs/abc-static/_/js/k=gapi.gapi.en.MGCxJbnW_Xw.O/am=AAAg/d=1/rs=AHpOoo9xa4htLEVH9xe6c4ToUehtTaLWvA/m=__features__",
					"https://apis.google.com", "", "", "", "", null, 1,
					"es_plusone_gc_20240708.1_p2", "ja", null, 0
				],
				[0.009999999776482582, "co.jp", "538", [
					["19040336", "19037049", "7", 1, 5, 2592000, "",
						"AN2NJM6vXyoFOaplGzWzX_d505hHHujpDg:1723887658161", 1, 1, 2,
						"https://www.google.com/_/og/promos/", 0
					], "n", "", ["", "", ""], 1, 2592000, null, null,
					"https://www.google.com/url?q=https://accounts.google.com/signin/v2/identifier%3Fec%3Dfutura_hpp_co_si_001_p%26continue%3Dhttps%253A%252F%252Fwww.google.com%252F%253Fptid%253D19027681%2526ptt%253D8%2526fpts%253D0&source=hpp&id=19040336&ct=7&usg=AOvVaw1q9uPMkSGEBSwcSPvCyoU0",
					null, null, null, null, null, 1, null, 0, null, 1, 0, 0, 0, null, null,
					0, 0, null, 0, 0, 0, 0, 1
				], null, null, null, 0],
				[1, null, null, 40400, 538, "JPN", "ja", "662508795.0", 8, null, 0, 0,
					null, null, null, null,
					"3700334,3700949,3701381,3701387,3701478,3701494,3701495", null, null,
					null, "KnDAZqHTCbu50-kPgvC2MA", 1, 0, 0, null, 2, 5, "ta", 70, 0, 0, 0,
					0, 1, 89978449, 0, 0
				],
				[
					[null, null, null,
						"https://www.gstatic.com/og/_/js/k=og.qtm.en_US.KZAWJ1ProoE.2019.O/rt=j/m=qabr,q_d,qcwid,qapid,qald,qads,q_dg/exm=qaaw,qadd,qaid,qein,qhaw,qhba,qhbr,qhch,qhga,qhid,qhin/d=1/ed=1/rs=AA2YrTv0taM5qVgw38gU_15kX9WFXe5TPw"
					],
					[null, null, null,
						"https://www.gstatic.com/og/_/ss/k=og.qtm.mfypcKMzPvw.L.W.O/m=qcwid,d_b_gm3,d_wi_gm3,d_lo_gm3/excm=qaaw,qadd,qaid,qein,qhaw,qhba,qhbr,qhch,qhga,qhid,qhin/d=1/ed=1/ct=zgms/rs=AA2YrTsXU5hjdOZrxXehYcpWx5cYm18ejw"
					]
				], null, null, null, [
					[
						[null, null, [null, null, null,
								"https://ogs.google.co.jp/widget/callout?prid=19040336&pgid=19037049&puid=30822bdd708a3c8b&eom=1&cce=1&dc=1"
							], 0, 280, 420, 70, 25, 0, null, 0, null, null, 8000, null, 71, 3,
							null, [19040336, 19037049, "", 1, 5,
								"AN2NJM6vXyoFOaplGzWzX_d505hHHujpDg:1723887658161", "", 0, 2592000,
								"30822bdd708a3c8b", 1, 2, 0,
								"https://www.google.com/url?q=https://accounts.google.com/signin/v2/identifier%3Fec%3Dfutura_hpp_co_si_001_p%26continue%3Dhttps%253A%252F%252Fwww.google.com%252F%253Fptid%253D19027681%2526ptt%253D8%2526fpts%253D0&source=hpp&id=19040336&ct=7&usg=AOvVaw1q9uPMkSGEBSwcSPvCyoU0",
								"https://www.google.com/_/og/promos/", 0, 0, 0, 0, 0, 0, 0, 89978449,
								0
							], 0, null, null, null, 0, null, 76, null, null, null, 107, 108, 109,
							"", null, null, null, 0, null, null, null, null, null, null, null,
							null, null, null, null, null, null, null, null, null, 0
						],
						[null, null, [null, null, null,
								"https://ogs.google.co.jp/widget/app/so?eom=1&awwd=1&gm3=1"
							], 0, 470, 370, 49, 4, 1, 0, 0, 63, 64, 8000,
							"https://www.google.co.jp/intl/ja/about/products", 67, 1, 69, null, 1,
							70,
							"アプリセットの読み込み中に問題が発生しました。しばらくしてからもう一度お試しください。または、%1$sGoogle サービス%2$sのページをご覧ください。",
							3, 0, 0, 74, 0, null, null, null, null, null, null, null,
							"/widget/app/so", null, null, null, null, null, null, null, 0, null,
							null, null, null, null, null, null, null, null, null, 0, null, 144
						],
						[null, null, [null, null, null,
								"https://ogs.google.co.jp/widget/callout?eom=1&dc=1"
							], null, 280, 420, 70, 25, 0, null, 0, null, null, 8000, null, 71, 4,
							null, null, null, null, null, null, null, null, 76, null, null, null,
							107, 108, 109, "", null, null, null, null, null, null, null, null,
							null, null, null, null, null, null, null, null, null, null, null, null,
							0
						]
					], null, null, "1", "538", 1, 0, null, "ja", 0, null, 0, 0, 0, [null,
						"https://www.google.co.jp/", null, null, null, 0, null, 0, 0, "", "",
						"92", "https://ogads-pa.googleapis.com", 0, 0, 0,
						"AN2NJM6vXyoFOaplGzWzX_d505hHHujpDg:1723887658161", "", 0, 0, 0, 86400,
						0, 0, 1, 0
					], 0, null, null, null, 0
				]
			]
		],
	};
	this.gbar_ = this.gbar_ || {};
	(function(_) {
		var window = this;
		try {
			_._F_toggles_initialize = function(a) {
				(typeof globalThis !== "undefined" ? globalThis : typeof self !==
					"undefined" ? self : this)._F_toggles = a || []
			};
			(0, _._F_toggles_initialize)([]);
			/*

			 Copyright The Closure Library Authors.
			 SPDX-License-Identifier: Apache-2.0
			*/
			var fa, ha, ma, oa, pa, ya, za, Ba, Ca, Da, Ga, La, Ya, Xa, $a, bb, ab, cb,
				db, gb, hb, lb, ob, ib, nb, mb, kb, jb, pb, qb, zb, Bb, Cb, Db, Eb;
			_.aa = function(a, b) {
				if (Error.captureStackTrace) Error.captureStackTrace(this, _.aa);
				else {
					const c = Error().stack;
					c && (this.stack = c)
				}
				a && (this.message = String(a));
				b !== void 0 && (this.cause = b)
			};
			_.ba = function(a) {
				_.t.setTimeout(() => {
					throw a;
				}, 0)
			};
			_.ca = function() {
				var a = _.t.navigator;
				return a && (a = a.userAgent) ? a : ""
			};
			fa = function(a) {
				return da ? ea ? ea.brands.some(({
					brand: b
				}) => b && b.indexOf(a) != -1) : !1 : !1
			};
			_.u = function(a) {
				return _.ca().indexOf(a) != -1
			};
			ha = function() {
				return da ? !!ea && ea.brands.length > 0 : !1
			};
			_.ia = function() {
				return ha() ? !1 : _.u("Opera")
			};
			_.ka = function() {
				return ha() ? !1 : _.u("Trident") || _.u("MSIE")
			};
			_.la = function() {
				return _.u("Firefox") || _.u("FxiOS")
			};
			_.na = function() {
				return _.u("Safari") && !(ma() || (ha() ? 0 : _.u("Coast")) || _.ia() ||
					(ha() ? 0 : _.u("Edge")) || (ha() ? fa("Microsoft Edge") : _.u("Edg/")) ||
					(ha() ? fa("Opera") : _.u("OPR")) || _.la() || _.u("Silk") || _.u(
						"Android"))
			};
			ma = function() {
				return ha() ? fa("Chromium") : (_.u("Chrome") || _.u("CriOS")) && !(ha() ?
					0 : _.u("Edge")) || _.u("Silk")
			};
			oa = function() {
				return da ? !!ea && !!ea.platform : !1
			};
			pa = function() {
				return _.u("iPhone") && !_.u("iPod") && !_.u("iPad")
			};
			_.qa = function() {
				return pa() || _.u("iPad") || _.u("iPod")
			};
			_.ra = function() {
				return oa() ? ea.platform === "macOS" : _.u("Macintosh")
			};
			_.ta = function(a, b) {
				return _.sa(a, b) >= 0
			};
			_.ua = function(a) {
				let b = "",
					c = 0;
				const d = a.length - 10240;
				for (; c < d;) b += String.fromCharCode.apply(null, a.subarray(c, c +=
					10240));
				b += String.fromCharCode.apply(null, c ? a.subarray(c) : a);
				return btoa(b)
			};
			_.va = function(a) {
				return a != null && a instanceof Uint8Array
			};
			_.wa = function(a) {
				return Array.prototype.slice.call(a)
			};
			_.xa = function(a) {
				return !!((a[_.v] | 0) & 2)
			};
			ya = function(a, b) {
				b[_.v] = (a | 0) & -14591
			};
			za = function(a, b) {
				b[_.v] = (a | 34) & -14557
			};
			Ba = function(a) {
				return !(!a || typeof a !== "object" || a.i !== Aa)
			};
			Ca = function(a) {
				return a !== null && typeof a === "object" && !Array.isArray(a) && a.constructor ===
					Object
			};
			Da = function(a, b, c) {
				if (!Array.isArray(a) || a.length) return !1;
				const d = a[_.v] | 0;
				if (d & 1) return !0;
				if (!(b && (Array.isArray(b) ? b.includes(c) : b.has(c)))) return !1;
				a[_.v] = d | 1;
				return !0
			};
			_.Ea = function(a) {
				if (a & 2) throw Error();
			};
			Ga = function(a, b) {
				(b = _.Fa ? b[_.Fa] : void 0) && (a[_.Fa] = _.wa(b))
			};
			_.Ia = function() {
				const a = Error();
				Ha(a, "incident");
				_.ba(a)
			};
			_.Ja = function(a) {
				a = Error(a);
				Ha(a, "warning");
				return a
			};
			_.Ka = function(a) {
				a.mj = !0;
				return a
			};
			La = function(a, b) {
				if (a.length > b.length) return !1;
				if (a.length < b.length || a === b) return !0;
				for (let c = 0; c < a.length; c++) {
					const d = a[c],
						e = b[c];
					if (d > e) return !1;
					if (d < e) return !0
				}
			};
			_.Na = function(a) {
				if (typeof a !== "boolean") throw Error("s`" + _.Ma(a) + "`" + a);
				return a
			};
			_.Oa = function(a) {
				if (!Number.isFinite(a)) throw _.Ja("enum");
				return a | 0
			};
			_.Pa = function(a) {
				if (typeof a !== "number") throw _.Ja("int32");
				if (!Number.isFinite(a)) throw _.Ja("int32");
				return a | 0
			};
			_.Qa = function(a) {
				if (a != null && typeof a !== "string") throw Error();
				return a
			};
			_.Ra = function(a) {
				return a == null || typeof a === "string" ? a : void 0
			};
			_.Ta = function(a, b, c) {
				if (a != null && typeof a === "object" && a.Bd === _.Sa) return a;
				if (Array.isArray(a)) {
					var d = a[_.v] | 0,
						e = d;
					e === 0 && (e |= c & 32);
					e |= c & 2;
					e !== d && (a[_.v] = e);
					return new b(a)
				}
			};
			_.Va = function(a, b) {
				Ua = b;
				a = new a(b);
				Ua = void 0;
				return a
			};
			_.Wa = function(a, b, c) {
				a == null && (a = Ua);
				Ua = void 0;
				if (a == null) {
					var d = 96;
					c ? (a = [c], d |= 512) : a = [];
					b && (d = d & -16760833 | (b & 1023) << 14)
				} else {
					if (!Array.isArray(a)) throw Error("t");
					d = a[_.v] | 0;
					if (d & 2048) throw Error("u");
					if (d & 64) return a;
					d |= 64;
					if (c && (d |= 512, c !== a[0])) throw Error("v");
					a: {
						c = a;
						const e = c.length;
						if (e) {
							const f = e - 1;
							if (Ca(c[f])) {
								d |= 256;
								b = f - (+!!(d & 512) - 1);
								if (b >= 1024) throw Error("w");
								d = d & -16760833 | (b & 1023) << 14;
								break a
							}
						}
						if (b) {
							b = Math.max(b, e - (+!!(d & 512) - 1));
							if (b > 1024) throw Error("x");
							d = d & -16760833 | (b & 1023) << 14
						}
					}
				}
				a[_.v] =
					d;
				return a
			};
			Ya = function(a, b) {
				return Xa(b)
			};
			Xa = function(a) {
				switch (typeof a) {
					case "number":
						return isFinite(a) ? a : String(a);
					case "boolean":
						return a ? 1 : 0;
					case "object":
						if (a)
							if (Array.isArray(a)) {
								if (Da(a, void 0, 0)) return
							} else {
								if (_.va(a)) return _.ua(a);
								if ("function" == typeof _.Za && a instanceof _.Za) return a.j()
							}
				}
				return a
			};
			$a = function(a, b, c) {
				const d = _.wa(a);
				var e = d.length;
				const f = b & 256 ? d[e - 1] : void 0;
				e += f ? -1 : 0;
				for (b = b & 512 ? 1 : 0; b < e; b++) d[b] = c(d[b]);
				if (f) {
					b = d[b] = {};
					for (const g in f) b[g] = c(f[g])
				}
				Ga(d, a);
				return d
			};
			bb = function(a, b, c, d, e) {
				if (a != null) {
					if (Array.isArray(a)) a = Da(a, void 0, 0) ? void 0 : e && (a[_.v] | 0) &
						2 ? a : ab(a, b, c, d !== void 0, e);
					else if (Ca(a)) {
						const f = {};
						for (let g in a) f[g] = bb(a[g], b, c, d, e);
						a = f
					} else a = b(a, d);
					return a
				}
			};
			ab = function(a, b, c, d, e) {
				const f = d || c ? a[_.v] | 0 : 0;
				d = d ? !!(f & 32) : void 0;
				const g = _.wa(a);
				for (let h = 0; h < g.length; h++) g[h] = bb(g[h], b, c, d, e);
				c && (Ga(g, a), c(f, g));
				return g
			};
			cb = function(a) {
				return a.Bd === _.Sa ? a.toJSON() : Xa(a)
			};
			db = function(a, b, c = za) {
				if (a != null) {
					if (a instanceof Uint8Array) return b ? a : new Uint8Array(a);
					if (Array.isArray(a)) {
						var d = a[_.v] | 0;
						if (d & 2) return a;
						b && (b = d === 0 || !!(d & 32) && !(d & 64 || !(d & 16)));
						return b ? (a[_.v] = (d | 34) & -12293, a) : ab(a, db, d & 4 ? za : c, !
							0, !0)
					}
					a.Bd === _.Sa && (c = a.ha, d = c[_.v], a = d & 2 ? a : _.Va(a.constructor,
						_.eb(c, d, !0)));
					return a
				}
			};
			_.eb = function(a, b, c) {
				const d = c || b & 2 ? za : ya,
					e = !!(b & 32);
				a = $a(a, b, f => db(f, e, d));
				a[_.v] = a[_.v] | 32 | (c ? 2 : 0);
				return a
			};
			_.fb = function(a) {
				const b = a.ha,
					c = b[_.v];
				return c & 2 ? _.Va(a.constructor, _.eb(b, c, !1)) : a
			};
			gb = function(a) {
				return a
			};
			hb = function(a) {
				return a
			};
			lb = function(a, b, c, d) {
				return ib(a, b, c, d, jb, kb)
			};
			ob = function(a, b, c, d) {
				return ib(a, b, c, d, mb, nb)
			};
			ib = function(a, b, c, d, e, f) {
				if (!c.length && !d) return 0;
				var g = 0;
				let h = 0,
					k = 0;
				var l = 0;
				let m = 0;
				for (var p = c.length - 1; p >= 0; p--) {
					var r = c[p];
					d && p === c.length - 1 && r === d || (l++, r != null && k++)
				}
				if (d)
					for (var q in d) p = +q, isNaN(p) || (m += pb(p), h++, p > g && (g = p));
				l = e(l, k) + f(h, g, m);
				q = k;
				p = h;
				r = g;
				let y = m;
				for (let B = c.length - 1; B >= 0; B--) {
					var D = c[B];
					if (D == null || d && B === c.length - 1 && D === d) continue;
					D = B - b;
					const H = e(D, q) + f(p, r, y);
					H < l && (a = 1 + D, l = H);
					p++;
					q--;
					y += pb(D);
					r = Math.max(r, D)
				}
				b = e(0, 0) + f(p, r, y);
				b < l && (a = 0, l = b);
				if (d) {
					p = h;
					r = g;
					y = m;
					q = k;
					for (const B in d) d = +B, isNaN(d) || d >= 1024 || (p--, q++, y -= B.length,
						g = e(d, q) + f(p, r, y), g < l && (a = 1 + d, l = g))
				}
				return a
			};
			nb = function(a, b, c) {
				return c + a * 3 + (a > 1 ? a - 1 : 0)
			};
			mb = function(a, b) {
				return (a > 1 ? a - 1 : 0) + (a - b) * 4
			};
			kb = function(a, b) {
				return a == 0 ? 0 : 9 * Math.max(1 << 32 - Math.clz32(a + a / 2 - 1), 4) <=
					b ? a == 0 ? 0 : a < 4 ? 100 + (a - 1) * 16 : a < 6 ? 148 + (a - 4) * 16 :
					a < 12 ? 244 + (a - 6) * 16 : a < 22 ? 436 + (a - 12) * 19 : a < 44 ?
					820 + (a - 22) * 17 : 52 + 32 * a : 40 + 4 * b
			};
			jb = function(a) {
				return 40 + 4 * a
			};
			pb = function(a) {
				return a >= 100 ? a >= 1E4 ? Math.ceil(Math.log10(1 + a)) : a < 1E3 ? 3 :
					4 : a < 10 ? 1 : 2
			};
			qb = function(a, b, c, d) {
				b = d + (+!!(b & 512) - 1);
				if (!(b < 0 || b >= a.length || b >= c)) return a[b]
			};
			_.sb = function(a, b, c, d, e) {
				const f = b >> 14 & 1023 || 536870912;
				if (c >= f || e && !rb) {
					let g = b;
					if (b & 256) e = a[a.length - 1];
					else {
						if (d == null) return g;
						e = a[f + (+!!(b & 512) - 1)] = {};
						g |= 256
					}
					e[c] = d;
					c < f && (a[c + (+!!(b & 512) - 1)] = void 0);
					g !== b && (a[_.v] = g);
					return g
				}
				a[c + (+!!(b & 512) - 1)] = d;
				b & 256 && (a = a[a.length - 1], c in a && delete a[c]);
				return b
			};
			_.ub = function(a, b, c, d) {
				a = a.ha;
				let e = a[_.v];
				const f = _.tb(a, e, c, d);
				b = _.Ta(f, b, e);
				b !== f && b != null && _.sb(a, e, c, b, d);
				return b
			};
			_.vb = function(a, b) {
				return a != null ? a : b
			};
			zb = function(a) {
				var b = wb ? a.ha : ab(a.ha, cb, void 0, void 0, !1); {
					var c = !wb;
					var d = xb ? void 0 : a.constructor.xj;
					var e = (c ? a.ha : b)[_.v];
					let E = b.length;
					if (E) {
						var f = b[E - 1],
							g = Ca(f);
						g ? E-- : f = void 0;
						a = +!!(e & 512) - 1;
						var h = E - a,
							k = !!yb && rb && !(e & 512),
							l;
						e = (l = yb) != null ? l : hb;
						e = k ? e(h, a, b, f) : h;
						l = (h = k && h !== e) ? Array.prototype.slice.call(b, 0, E) : b;
						if (g || h) {
							b: {
								var m = l;
								var p = f;
								g = {};
								k = !1;
								if (h)
									for (var r = Math.max(0, e + a); r < m.length; r++) {
										var q = m[r],
											y = r - a;
										q == null || Da(q, d, y) || Ba(q) && q.size === 0 || (m[r] = void 0,
											g[y] = q, k = !0)
									}
								if (p)
									for (var D in p)
										if (r = +D, isNaN(r)) g[D] = p[D];
										else if (q = p[D], Array.isArray(q) && (Da(q, d, +D) || Ba(q) && q.size ===
										0) && (q = null), q == null && (k = !0), h && r < e) {
									k = !0;
									q = r + a;
									for (y = m.length; y <= q; y++) m.push(void 0);
									m[q] = p[r]
								} else q != null && (g[D] = q);
								if (k) {
									for (var B in g) {
										p = g;
										break b
									}
									p = null
								}
							}
							m = p == null ? f != null : p !== f
						}
						h && (E = l.length);
						for (var H; E > 0; E--) {
							B = E - 1;
							D = l[B];
							B -= a;
							if (!(D == null || Da(D, d, B) || Ba(D) && D.size === 0)) break;
							H = !0
						}
						if (l !== b || m || H) {
							if (!h && !c) l = Array.prototype.slice.call(l, 0, E);
							else if (H || m || p) l.length = E;
							p && l.push(p)
						}
						b = l
					}
				}
				return b
			};
			_.w = function(a, b) {
				return a != null ? !!a : !!b
			};
			_.x = function(a, b) {
				b == void 0 && (b = "");
				return a != null ? a : b
			};
			_.Ab = function(a) {
				for (const b in a) return !1;
				return !0
			};
			Bb = typeof Object.defineProperties == "function" ? Object.defineProperty :
				function(a, b, c) {
					if (a == Array.prototype || a == Object.prototype) return a;
					a[b] = c.value;
					return a
				};
			Cb = function(a) {
				a = ["object" == typeof globalThis && globalThis, a, "object" == typeof window &&
					window, "object" == typeof self && self, "object" == typeof global &&
					global
				];
				for (var b = 0; b < a.length; ++b) {
					var c = a[b];
					if (c && c.Math == Math) return c
				}
				throw Error("a");
			};
			Db = Cb(this);
			Eb = function(a, b) {
				if (b) a: {
					var c = Db;
					a = a.split(".");
					for (var d = 0; d < a.length - 1; d++) {
						var e = a[d];
						if (!(e in c)) break a;
						c = c[e]
					}
					a = a[a.length - 1];
					d = c[a];
					b = b(d);
					b != d && b != null && Bb(c, a, {
						configurable: !0,
						writable: !0,
						value: b
					})
				}
			};
			Eb("Symbol.dispose", function(a) {
				return a ? a : Symbol("b")
			});
			Eb("globalThis", function(a) {
				return a || Db
			});
			Eb("Promise.prototype.finally", function(a) {
				return a ? a : function(b) {
					return this.then(function(c) {
						return Promise.resolve(b()).then(function() {
							return c
						})
					}, function(c) {
						return Promise.resolve(b()).then(function() {
							throw c;
						})
					})
				}
			});
			var Hb, Ib, Lb;
			_.Fb = _.Fb || {};
			_.t = this || self;
			Hb = function(a, b) {
				var c = _.Gb("WIZ_global_data.oxN3nb");
				a = c && c[a];
				return a != null ? a : b
			};
			Ib = _.t._F_toggles || [];
			_.Gb = function(a, b) {
				a = a.split(".");
				b = b || _.t;
				for (var c = 0; c < a.length; c++)
					if (b = b[a[c]], b == null) return null;
				return b
			};
			_.Ma = function(a) {
				var b = typeof a;
				return b != "object" ? b : a ? Array.isArray(a) ? "array" : b : "null"
			};
			_.Jb = function(a) {
				var b = typeof a;
				return b == "object" && a != null || b == "function"
			};
			_.Kb = "closure_uid_" + (Math.random() * 1E9 >>> 0);
			Lb = function(a, b, c) {
				return a.call.apply(a.bind, arguments)
			};
			_.z = function(a, b, c) {
				_.z = Lb;
				return _.z.apply(null, arguments)
			};
			_.A = function(a, b) {
				a = a.split(".");
				var c = _.t;
				a[0] in c || typeof c.execScript == "undefined" || c.execScript("var " +
					a[0]);
				for (var d; a.length && (d = a.shift());) a.length || b === void 0 ? c[d] &&
					c[d] !== Object.prototype[d] ? c = c[d] : c = c[d] = {} : c[d] = b
			};
			_.C = function(a, b) {
				function c() {}
				c.prototype = b.prototype;
				a.W = b.prototype;
				a.prototype = new c;
				a.prototype.constructor = a;
				a.ej = function(d, e, f) {
					for (var g = Array(arguments.length - 2), h = 2; h < arguments.length; h++)
						g[h - 2] = arguments[h];
					return b.prototype[e].apply(d, g)
				}
			};
			_.C(_.aa, Error);
			_.aa.prototype.name = "CustomError";
			var Mb = !!(Ib[0] & 8192),
				Nb = !!(Ib[0] & 256),
				Ob = !!(Ib[0] >> 14 & 1),
				Pb = !!(Ib[0] & 128),
				Qb = !!(Ib[0] & 16);
			var Rb = Hb(1, !0),
				da = Mb ? Ob : Hb(610401301, !1),
				rb = Mb ? Nb || !Qb : Hb(645172343, Rb);
			var xb = Mb ? Nb || !Pb : Hb(188588736, !0);
			_.Sb = typeof TextDecoder !== "undefined";
			_.Tb = typeof TextEncoder !== "undefined";
			_.Vb = function() {
				return _.ca().toLowerCase().indexOf("webkit") != -1
			};
			var ea, Wb = _.t.navigator;
			ea = Wb ? Wb.userAgentData || null : null;
			_.sa = function(a, b) {
				return Array.prototype.indexOf.call(a, b, void 0)
			};
			_.Xb = function(a, b, c) {
				Array.prototype.forEach.call(a, b, c)
			};
			_.Yb = function(a) {
				_.Yb[" "](a);
				return a
			};
			_.Yb[" "] = function() {};
			var kc;
			_.Zb = _.ia();
			_.$b = _.ka();
			_.ac = _.u("Edge");
			_.bc = _.u("Gecko") && !(_.Vb() && !_.u("Edge")) && !(_.u("Trident") || _.u(
				"MSIE")) && !_.u("Edge");
			_.cc = _.Vb() && !_.u("Edge");
			_.dc = _.ra();
			_.ec = oa() ? ea.platform === "Windows" : _.u("Windows");
			_.fc = oa() ? ea.platform === "Android" : _.u("Android");
			_.gc = pa();
			_.hc = _.u("iPad");
			_.ic = _.u("iPod");
			_.jc = _.qa();
			a: {
				var lc = "",
					mc = function() {
						var a = _.ca();
						if (_.bc) return /rv:([^\);]+)(\)|;)/.exec(a);
						if (_.ac) return /Edge\/([\d\.]+)/.exec(a);
						if (_.$b) return /\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);
						if (_.cc) return /WebKit\/(\S+)/.exec(a);
						if (_.Zb) return /(?:Version)[ \/]?(\S+)/.exec(a)
					}();
				mc && (lc = mc ? mc[1] : "");
				if (_.$b) {
					var nc, oc = _.t.document;
					nc = oc ? oc.documentMode : void 0;
					if (nc != null && nc > parseFloat(lc)) {
						kc = String(nc);
						break a
					}
				}
				kc = lc
			}
			_.pc = kc;
			_.qc = _.la();
			_.rc = pa() || _.u("iPod");
			_.sc = _.u("iPad");
			_.tc = _.u("Android") && !(ma() || _.la() || _.ia() || _.u("Silk"));
			_.uc = ma();
			_.vc = _.na() && !_.qa();
			var wc;
			_.v = Symbol();
			wc = Symbol();
			_.xc = Symbol();
			_.yc = Symbol();
			var Aa, Ac;
			_.Sa = {};
			Aa = {};
			Ac = [];
			Ac[_.v] = 55;
			_.zc = Object.freeze(Ac);
			_.Bc = Object.freeze({});
			Object.freeze({});
			_.Cc = Object.freeze({});
			var Ha = function(a, b) {
				a.__closure__error__context__984382 || (a.__closure__error__context__984382 = {});
				a.__closure__error__context__984382.severity = b
			};
			var Dc;
			_.Ec = _.Ka(a => typeof a === "number");
			_.Fc = _.Ka(a => typeof a === "string");
			_.Gc = _.Ka(a => typeof a === "boolean");
			_.Hc = typeof _.t.BigInt === "function" && typeof _.t.BigInt(0) ===
				"bigint";
			var Kc, Ic, Lc, Jc;
			_.Mc = _.Ka(a => _.Hc ? a >= Ic && a <= Jc : a[0] === "-" ? La(a, Kc) : La(
				a, Lc));
			Kc = Number.MIN_SAFE_INTEGER.toString();
			Ic = _.Hc ? BigInt(Number.MIN_SAFE_INTEGER) : void 0;
			Lc = Number.MAX_SAFE_INTEGER.toString();
			Jc = _.Hc ? BigInt(Number.MAX_SAFE_INTEGER) : void 0;
			var Ua;
			_.Nc = function(a, b) {
				a = a.ha;
				return _.tb(a, a[_.v], b)
			};
			_.tb = function(a, b, c, d) {
				if (c === -1) return null;
				const e = b >> 14 & 1023 || 536870912;
				if (c >= e) {
					if (b & 256) return a[a.length - 1][c]
				} else {
					var f = a.length;
					if (d && b & 256 && (d = a[f - 1][c], d != null)) {
						if (qb(a, b, e, c) && wc != null) {
							var g;
							a = (g = Dc) != null ? g : Dc = {};
							g = a[wc] || 0;
							g >= 4 || (a[wc] = g + 1, _.Ia())
						}
						return d
					}
					return qb(a, b, e, c)
				}
			};
			_.Oc = function(a, b, c) {
				const d = a.ha;
				let e = d[_.v];
				_.Ea(e);
				_.sb(d, e, b, c);
				return a
			};
			_.F = function(a, b, c, d = !1) {
				b = _.ub(a, b, c, d);
				if (b == null) return b;
				a = a.ha;
				let e = a[_.v];
				if (!(e & 2)) {
					const f = _.fb(b);
					f !== b && (b = f, _.sb(a, e, c, b, d))
				}
				return b
			};
			_.G = function(a, b, c) {
				c == null && (c = void 0);
				return _.Oc(a, b, c)
			};
			_.I = function(a, b) {
				a = _.Nc(a, b);
				return a == null || typeof a === "boolean" ? a : typeof a === "number" ?
					!!a : void 0
			};
			_.J = function(a, b) {
				return _.Ra(_.Nc(a, b))
			};
			_.K = function(a, b, c = !1) {
				return _.vb(_.I(a, b), c)
			};
			_.L = function(a, b) {
				return _.vb(_.J(a, b), "")
			};
			_.M = function(a, b, c) {
				return _.Oc(a, b, c == null ? c : _.Na(c))
			};
			_.N = function(a, b, c) {
				return _.Oc(a, b, c == null ? c : _.Pa(c))
			};
			_.O = function(a, b, c) {
				return _.Oc(a, b, _.Qa(c))
			};
			_.P = function(a, b, c) {
				return _.Oc(a, b, c == null ? c : _.Oa(c))
			};
			var yb, wb;
			_.Q = class {
				constructor(a, b, c) {
					this.ha = _.Wa(a, b, c)
				}
				toJSON() {
					return zb(this)
				}
				Ca(a) {
					try {
						return wb = !0, a && (yb = a === hb || a !== gb && a !== lb && a !==
							ob ? hb : a), JSON.stringify(zb(this), Ya)
					} finally {
						a && (yb = void 0), wb = !1
					}
				}
				rc() {
					return _.xa(this.ha)
				}
			};
			_.Q.prototype.Bd = _.Sa;
			_.Q.prototype.toString = function() {
				try {
					return wb = !0, zb(this).toString()
				} finally {
					wb = !1
				}
			};
			_.Pc = Symbol();
			_.Qc = Symbol();
			_.Rc = Symbol();
			_.Sc = Symbol();
			_.Tc = Symbol();
			var Uc = class extends _.Q {
				constructor() {
					super()
				}
			};
			_.Vc = class extends _.Q {
				constructor() {
					super()
				}
				D(a) {
					return _.N(this, 3, a)
				}
			};
			var Wc = class extends _.Q {
				constructor(a) {
					super(a)
				}
				Jc(a) {
					return _.O(this, 24, a)
				}
			};
			_.Xc = class extends _.Q {
				constructor(a) {
					super(a)
				}
			};
			_.R = function() {
				this.qa = this.qa;
				this.Y = this.Y
			};
			_.R.prototype.qa = !1;
			_.R.prototype.isDisposed = function() {
				return this.qa
			};
			_.R.prototype.dispose = function() {
				this.qa || (this.qa = !0, this.R())
			};
			_.R.prototype[Symbol.dispose] = function() {
				this.dispose()
			};
			_.R.prototype.R = function() {
				if (this.Y)
					for (; this.Y.length;) this.Y.shift()()
			};
			var Yc = class extends _.R {
				constructor() {
					var a = window;
					super();
					this.o = a;
					this.i = [];
					this.j = {}
				}
				resolve(a) {
					var b = this.o;
					a = a.split(".");
					for (var c = a.length, d = 0; d < c; ++d)
						if (b[a[d]]) b = b[a[d]];
						else return null;
					return b instanceof Function ? b : null
				}
				yb() {
					for (var a = this.i.length, b = this.i, c = [], d = 0; d < a; ++d) {
						var e = b[d].i(),
							f = this.resolve(e);
						if (f && f != this.j[e]) try {
							b[d].yb(f)
						} catch (g) {} else c.push(b[d])
					}
					this.i = c.concat(b.slice(a))
				}
			};
			var $c = class extends _.R {
				constructor() {
					var a = _.Zc;
					super();
					this.o = a;
					this.A = this.i = null;
					this.v = 0;
					this.B = {};
					this.j = !1;
					a = window.navigator.userAgent;
					a.indexOf("MSIE") >= 0 && a.indexOf("Trident") >= 0 && (a =
							/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a)) && a[1] && parseFloat(a[1]) <
						9 && (this.j = !0)
				}
				C(a, b) {
					this.i = b;
					this.A = a;
					b.preventDefault ? b.preventDefault() : b.returnValue = !1
				}
			};
			_.ad = class extends _.Q {
				constructor(a) {
					super(a)
				}
			};
			var bd = class extends _.Q {
				constructor(a) {
					super(a)
				}
			};
			var ed;
			_.cd = function(a, b, c = 98, d = new _.Vc) {
				if (a.i) {
					const e = new Uc;
					_.O(e, 1, b.message);
					_.O(e, 2, b.stack);
					_.N(e, 3, b.lineNumber);
					_.P(e, 5, 1);
					_.G(d, 40, e);
					a.i.log(c, d)
				}
			};
			ed = class {
				constructor() {
					var a = dd;
					this.i = null;
					_.K(a, 4, !0)
				}
				log(a, b, c = new _.Vc) {
					_.cd(this, a, 98, c)
				}
			};
			var fd, gd;
			fd = function(a) {
				if (a.o.length > 0) {
					var b = a.i !== void 0,
						c = a.j !== void 0;
					if (b || c) {
						b = b ? a.v : a.A;
						c = a.o;
						a.o = [];
						try {
							_.Xb(c, b, a)
						} catch (d) {
							console.error(d)
						}
					}
				}
			};
			_.hd = class {
				constructor(a) {
					this.i = a;
					this.j = void 0;
					this.o = []
				}
				then(a, b, c) {
					this.o.push(new gd(a, b, c));
					fd(this)
				}
				resolve(a) {
					if (this.i !== void 0 || this.j !== void 0) throw Error("B");
					this.i = a;
					fd(this)
				}
				reject(a) {
					if (this.i !== void 0 || this.j !== void 0) throw Error("B");
					this.j = a;
					fd(this)
				}
				v(a) {
					a.j && a.j.call(a.i, this.i)
				}
				A(a) {
					a.o && a.o.call(a.i, this.j)
				}
			};
			gd = class {
				constructor(a, b, c) {
					this.j = a;
					this.o = b;
					this.i = c
				}
			};
			_.id = a => {
				var b = "oc";
				if (a.oc && a.hasOwnProperty(b)) return a.oc;
				b = new a;
				return a.oc = b
			};
			_.jd = class {
				constructor() {
					this.v = new _.hd;
					this.i = new _.hd;
					this.D = new _.hd;
					this.B = new _.hd;
					this.C = new _.hd;
					this.A = new _.hd;
					this.o = new _.hd;
					this.j = new _.hd;
					this.F = new _.hd
				}
				K() {
					return this.v
				}
				M() {
					return this.i
				}
				N() {
					return this.D
				}
				L() {
					return this.B
				}
				qa() {
					return this.C
				}
				Y() {
					return this.A
				}
				J() {
					return this.o
				}
				G() {
					return this.j
				}
				static i() {
					return _.id(_.jd)
				}
			};
			var od;
			_.ld = function() {
				return _.F(_.kd, Wc, 1)
			};
			_.md = function() {
				return _.F(_.kd, _.Xc, 5)
			};
			od = class extends _.Q {
				constructor() {
					super(nd)
				}
			};
			var nd;
			window.gbar_ && window.gbar_.CONFIG ? nd = window.gbar_.CONFIG[0] || {} :
				nd = [];
			_.kd = new od;
			var dd = _.F(_.kd, bd, 3) || new bd;
			_.ld() || new Wc;
			_.Zc = new ed;
			_.A("gbar_._DumpException", function(a) {
				_.Zc ? _.Zc.log(a) : console.error(a)
			});
			_.pd = new $c;
			var rd;
			_.sd = function(a, b) {
				var c = _.qd.i();
				if (a in c.i) {
					if (c.i[a] != b) throw new rd;
				} else {
					c.i[a] = b;
					const h = c.j[a];
					if (h)
						for (let k = 0, l = h.length; k < l; k++) {
							b = h[k];
							var d = c.i;
							delete b.i[a];
							if (_.Ab(b.i)) {
								for (var e = b.j.length, f = Array(e), g = 0; g < e; g++) f[g] = d[b.j[
									g]];
								b.o.apply(b.v, f)
							}
						}
					delete c.j[a]
				}
			};
			_.qd = class {
				constructor() {
					this.i = {};
					this.j = {}
				}
				static i() {
					return _.id(_.qd)
				}
			};
			_.td = class extends _.aa {
				constructor() {
					super()
				}
			};
			rd = class extends _.td {};
			_.A("gbar.A", _.hd);
			_.hd.prototype.aa = _.hd.prototype.then;
			_.A("gbar.B", _.jd);
			_.jd.prototype.ba = _.jd.prototype.M;
			_.jd.prototype.bb = _.jd.prototype.N;
			_.jd.prototype.bd = _.jd.prototype.qa;
			_.jd.prototype.bf = _.jd.prototype.K;
			_.jd.prototype.bg = _.jd.prototype.L;
			_.jd.prototype.bh = _.jd.prototype.Y;
			_.jd.prototype.bj = _.jd.prototype.J;
			_.jd.prototype.bk = _.jd.prototype.G;
			_.A("gbar.a", _.jd.i());
			window.gbar && window.gbar.ap && window.gbar.ap(window.gbar.a);
			var ud = new Yc;
			_.sd("api", ud);
			var vd = _.md() || new _.Xc,
				wd = window,
				xd = _.x(_.J(vd, 8));
			wd.__PVT = xd;
			_.sd("eq", _.pd);
		} catch (e) {
			_._DumpException(e)
		}
		try {
			_.yd = class extends _.Q {
				constructor(a) {
					super(a)
				}
			};
		} catch (e) {
			_._DumpException(e)
		}
		try {
			var zd = class extends _.Q {
				constructor() {
					super()
				}
			};
			var Ad = class extends _.R {
				constructor() {
					super();
					this.j = [];
					this.i = []
				}
				o(a, b) {
					this.j.push({
						features: a,
						options: b
					})
				}
				init(a, b, c) {
					window.gapi = {};
					var d = window.___jsl = {};
					d.h = _.x(_.J(a, 1));
					_.I(a, 12) != null && (d.dpo = _.w(_.K(a, 12)));
					d.ms = _.x(_.J(a, 2));
					d.m = _.x(_.J(a, 3));
					d.l = [];
					_.L(b, 1) && (a = _.J(b, 3)) && this.i.push(a);
					_.L(c, 1) && (c = _.J(c, 2)) && this.i.push(c);
					_.A("gapi.load", (0, _.z)(this.o, this));
					return this
				}
			};
			var Bd = _.F(_.kd, _.ad, 14);
			if (Bd) {
				var Cd = _.F(_.kd, _.yd, 9) || new _.yd,
					Dd = new zd,
					Ed = new Ad;
				Ed.init(Bd, Cd, Dd);
				_.sd("gs", Ed)
			};
		} catch (e) {
			_._DumpException(e)
		}
	})(this.gbar_);
	// Google Inc.

	</script>
	<style>
	h1,ol,ul,li,button{margin:0;padding:0}button{border:none;background:none}body{background:#fff}body,input,button{font-size:14px;font-family:Arial,sans-serif;color:var(--COEmY)}a{color:var(--JKqx2);text-decoration:none}a:hover,a:active{text-decoration:underline}a:visited{color:#681da8}html,body{min-width:400px}body,html{height:100%;margin:0;padding:0}.gb_9a:not(.gb_bd){font:13px/27px Roboto,Arial,sans-serif;z-index:986}.gb_r{display:none}.gb_ha,.gb_dd{font-family:"Google Sans Text",Roboto,Helvetica,Arial,sans-serif;font-style:normal}a.gb_va{-webkit-border-radius:100px;border-radius:100px;background:#0b57d0;background:var(--gm3-sys-color-primary,#0b57d0);-webkit-box-sizing:border-box;box-sizing:border-box;color:#fff;color:var(--gm3-sys-color-on-primary,#fff);display:inline-block;font-size:14px;font-weight:500;min-height:40px;outline:none;padding:10px 24px;text-align:center;text-decoration:none;white-space:normal;line-height:18px;position:relative}a.gb_wa{-webkit-border-radius:100px;border-radius:100px;border:1px solid;border-color:#747775;border-color:var(--gm3-sys-color-outline,#747775);background:none;-webkit-box-sizing:border-box;box-sizing:border-box;color:#0b57d0;color:var(--gm3-sys-color-primary,#0b57d0);display:inline-block;font-size:14px;font-weight:500;min-height:40px;outline:none;padding:10px 24px;text-align:center;text-decoration:none;white-space:normal;line-height:18px;position:relative}.gb_Aa.gb_i a.gb_va,.gb_Ba.gb_i a.gb_va{background:#a8c7fa;background:var(--gm3-sys-color-primary,#a8c7fa);color:#062e6f;color:var(--gm3-sys-color-on-primary,#062e6f)}.gb_Ca.gb_i a.gb_va{background:#c2e7ff;background:var(--gm3-sys-color-secondary-container,#c2e7ff);color:#001d35;color:var(--gm3-sys-color-on-secondary-container,#001d35)}.gb_ha.gb_i a.gb_wa{color:#a8c7fa;color:var(--gm3-sys-color-primary,#a8c7fa)}a.gb_ed{padding:10px 12px;margin:12px 16px 12px 10px;min-width:85px}@media (max-width:640px){a.gb_ed{min-width:75px}}.gb_ha.gb_Aa{color:#1f1f1f;color:var(--gm3-sys-color-on-surface,#1f1f1f)}.gb_ha.gb_Aa.gb_fd{background:#fff;background:var(--gm3-sys-color-background,#fff)}.gb_ha.gb_Aa .gb_6c.gb_7c,.gb_ha.gb_Aa a.gb_y,.gb_ha.gb_Aa span.gb_y,.gb_ha.gb_Aa .gb_8c .gb_gd,.gb_ha.gb_Aa .gb_Xc .gb_gd{color:#1f1f1f;color:var(--gm3-sys-color-on-surface,#1f1f1f)}.gb_ha.gb_Aa svg{color:#444746;color:var(--gm3-sys-color-on-surface-variant,#444746)}.gb_ha.gb_i.gb_Aa{color:#e3e3e3;color:var(--gm3-sys-color-on-surface,#e3e3e3)}.gb_ha.gb_i.gb_Aa.gb_fd{background:transparent}.gb_ha.gb_i.gb_Aa .gb_6c.gb_7c,.gb_ha.gb_i.gb_Aa a.gb_y,.gb_ha.gb_i.gb_Aa span.gb_y,.gb_ha.gb_i.gb_Aa .gb_8c .gb_gd,.gb_ha.gb_i.gb_Aa .gb_Xc .gb_gd{color:#e3e3e3;color:var(--gm3-sys-color-on-surface,#e3e3e3)}.gb_ha.gb_i.gb_Aa svg{color:#c4c7c5;color:var(--gm3-sys-color-on-surface-variant,#c4c7c5)}.gb_ha.gb_i.gb_Aa.gb_fd{background:#1f1f1f;background:var(--gm3-sys-color-background,#1f1f1f)}.gb_ha.gb_Ba{color:#1f1f1f;color:var(--gm3-sys-color-on-surface,#1f1f1f)}.gb_ha.gb_Ba.gb_fd{background:#e9eef6;background:var(--gm3-sys-color-surface-container-high,#e9eef6)}.gb_ha.gb_Ba .gb_6c.gb_7c,.gb_ha.gb_Ba a.gb_y,.gb_ha.gb_Ba span.gb_y,.gb_ha.gb_Ba .gb_8c .gb_gd,.gb_ha.gb_Ba .gb_Xc .gb_gd{color:#1f1f1f;color:var(--gm3-sys-color-on-surface,#1f1f1f)}.gb_ha.gb_Ba svg{color:#444746;color:var(--gm3-sys-color-on-surface-variant,#444746)}.gb_ha.gb_i.gb_Ba{color:#e3e3e3;color:var(--gm3-sys-color-on-surface,#e3e3e3)}.gb_ha.gb_i.gb_Ba.gb_fd{background:#282a2c;background:var(--gm3-sys-color-surface-container-high,#282a2c)}.gb_ha.gb_i.gb_Ba .gb_6c.gb_7c,.gb_ha.gb_i.gb_Ba a.gb_y,.gb_ha.gb_i.gb_Ba span.gb_y,.gb_ha.gb_i.gb_Ba .gb_8c .gb_gd,.gb_ha.gb_i.gb_Ba .gb_Xc .gb_gd{color:#e3e3e3;color:var(--gm3-sys-color-on-surface,#e3e3e3)}.gb_ha.gb_i.gb_Ba svg{color:#c4c7c5;color:var(--gm3-sys-color-on-surface-variant,#c4c7c5)}.gb_ha.gb_Ca{color:#1f1f1f;color:var(--gm3-sys-color-on-surface,#1f1f1f)}.gb_ha.gb_Ca.gb_fd{background:transparent}.gb_ha.gb_Ca .gb_6c.gb_7c,.gb_ha.gb_Ca a.gb_y,.gb_ha.gb_Ca span.gb_y,.gb_ha.gb_Ca .gb_8c .gb_gd,.gb_ha.gb_Ca .gb_Xc .gb_gd{color:#1f1f1f;color:var(--gm3-sys-color-on-surface,#1f1f1f)}.gb_ha.gb_Ca svg{color:#444746;color:var(--gm3-sys-color-on-surface-variant,#444746)}.gb_ha.gb_Ca.gb_i.gb_fd{background:transparent}.gb_ha.gb_Ca.gb_i .gb_6c.gb_7c,.gb_ha.gb_Ca.gb_i a.gb_y,.gb_ha.gb_Ca.gb_i span.gb_y,.gb_ha.gb_Ca.gb_i .gb_8c .gb_gd,.gb_ha.gb_Ca.gb_i .gb_Xc .gb_gd,.gb_ha.gb_Ca.gb_i svg{color:white;color:var(--og-theme-color,white)}.gb_ha a.gb_y,.gb_ha span.gb_y{text-decoration:none}.gb_6c{font-family:Google Sans,Roboto,Helvetica,Arial,sans-serif;font-size:20px;font-weight:400;letter-spacing:.25px;line-height:48px;margin-bottom:2px;opacity:1;overflow:hidden;padding-left:16px;position:relative;text-overflow:ellipsis;vertical-align:middle;top:2px;white-space:nowrap;-webkit-flex:1 1 auto;-webkit-box-flex:1;flex:1 1 auto}.gb_ha.gb_Ja .gb_6c{margin-bottom:0}.gb_8c.gb_9c .gb_6c{padding-left:4px}.gb_ha.gb_Ja .gb_ad{position:relative;top:-2px}.gb_ha{min-width:160px;position:relative}.gb_ha.gb_Pc{min-width:120px}.gb_ha.gb_hd .gb_id{display:none}.gb_ha.gb_hd .gb_jd{height:56px}header.gb_ha{display:block}.gb_ha svg{fill:currentColor}.gb_kd{position:fixed;top:0;width:100%}.gb_ld{-webkit-box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2);box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2)}.gb_md{height:64px}.gb_jd{-webkit-box-sizing:border-box;box-sizing:border-box;position:relative;width:100%;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-pack:space-between;-webkit-justify-content:space-between;justify-content:space-between;min-width:-webkit-min-content;min-width:min-content}.gb_ha:not(.gb_Ja) .gb_jd{padding:8px}.gb_ha:not(.gb_Ja) .gb_jd a.gb_nd{margin:12px 8px 12px 10px}.gb_ha.gb_od .gb_jd{-webkit-flex:1 0 auto;-webkit-box-flex:1;flex:1 0 auto}.gb_ha .gb_jd.gb_pd.gb_qd{min-width:0}.gb_ha.gb_Ja .gb_jd{padding:4px;padding-left:8px;min-width:0}.gb_ha.gb_Ja .gb_jd a.gb_nd{margin:12px 8px 12px 10px}.gb_id{height:48px;vertical-align:middle;white-space:nowrap;-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-user-select:none}.gb_sd>.gb_id{display:table-cell;width:100%}.gb_8c{padding-right:25px;box-sizing:border-box;-webkit-flex:1 0 auto;-webkit-box-flex:1;flex:1 0 auto}.gb_ha.gb_Ja .gb_8c{padding-right:14px}.gb_td{-webkit-flex:1 1 100%;-webkit-box-flex:1;flex:1 1 100%}.gb_td>:only-child{display:inline-block}.gb_ud.gb_Zc{padding-left:4px}.gb_ud.gb_vd,.gb_ha.gb_od .gb_ud,.gb_ha.gb_Ja:not(.gb_dd) .gb_ud{padding-left:0}.gb_ha.gb_Ja .gb_ud.gb_vd{padding-right:0}.gb_ha.gb_Ja .gb_ud.gb_vd .gb_xa{margin-left:10px}.gb_Zc{display:inline}.gb_ha.gb_Sc .gb_ud.gb_wd,.gb_ha.gb_dd .gb_ud.gb_wd{padding-left:2px}.gb_6c{display:inline-block}.gb_ud{-webkit-box-sizing:border-box;box-sizing:border-box;height:48px;padding:0 4px;padding-left:5px;-webkit-flex:0 0 auto;-webkit-box-flex:0;flex:0 0 auto;-webkit-box-pack:flex-end;-webkit-justify-content:flex-end;justify-content:flex-end}.gb_dd{height:48px}.gb_ha.gb_dd{min-width:auto}.gb_dd .gb_ud{float:right;padding-left:32px;padding-left:var(--og-bar-parts-side-padding,32px)}.gb_dd .gb_ud.gb_xd{padding-left:0}.gb_yd{font-size:14px;max-width:200px;overflow:hidden;padding:0 12px;text-overflow:ellipsis;white-space:nowrap;-webkit-user-select:text}.gb_Mc a{color:inherit}.gb_7c{text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased;opacity:1}.gb_zd{position:relative}.gb_o{font-family:arial,sans-serif;line-height:normal;padding-right:15px}.gb_z{display:inline-block;padding-left:15px}.gb_z .gb_y{display:inline-block;line-height:24px;vertical-align:middle}.gb_Ad{text-align:left}.gb_l{display:none}@media screen and (max-width:319px){.gb_jd:not(.gb_pd) .gb_k{display:none;visibility:hidden}}.gb_k .gb_d,.gb_k .gb_d:hover,.gb_k .gb_d:focus{opacity:1}.gb_n{display:none}.gb_m{display:none!important}.gb_Ta{visibility:hidden}@media screen and (max-width:319px){.gb_jd:not(.gb_pd) .gb_k{display:none;visibility:hidden}}.gb_Fd{display:inline-block;vertical-align:middle}.gb_Id .gb_r{bottom:-3px;right:-5px}.gb_f{position:relative}.gb_d{display:inline-block;outline:none;vertical-align:middle;-webkit-border-radius:50%;border-radius:50%;-webkit-box-sizing:border-box;box-sizing:border-box;height:40px;width:40px;cursor:pointer;text-decoration:none}#gb#gb a.gb_d{cursor:pointer;text-decoration:none}.gb_d,a.gb_d{color:#000}x:-o-prefocus{border-bottom-color:#ccc}.gb_W{background:#fff;border:1px solid #ccc;border-color:rgba(0,0,0,.2);color:#000;-webkit-box-shadow:0 2px 10px rgba(0,0,0,.2);box-shadow:0 2px 10px rgba(0,0,0,.2);display:none;outline:none;overflow:hidden;position:absolute;right:0;top:54px;-webkit-animation:gb__a .2s;-webkit-animation:gb__a .2s;animation:gb__a .2s;-webkit-border-radius:2px;border-radius:2px;-webkit-user-select:text}.gb_Fd.gb_Ea .gb_W,.gb_Ea.gb_W{display:block}.gb_Jd{position:absolute;right:0;top:54px;z-index:-1}.gb_0a .gb_W{margin-top:-10px}.gb_Fd:first-child{padding-left:4px}.gb_ha.gb_Kd .gb_Fd:first-child{padding-left:0}.gb_Ld{position:relative}.gb_Xc .gb_Ld,.gb_dd .gb_Ld{float:right}.gb_d{padding:8px;cursor:pointer}.gb_Md button svg,.gb_d{-webkit-border-radius:50%;border-radius:50%}.gb_Fd{padding:4px}.gb_ha.gb_Kd .gb_Fd{padding:4px 2px}.gb_ha.gb_Kd .gb_b.gb_Fd{padding-left:6px}.gb_W{z-index:991;line-height:normal}.gb_W.gb_Nd{left:0;right:auto}@media (max-width:350px){.gb_W.gb_Nd{left:0}}.gb_Od .gb_W{top:56px}.gb_q{-webkit-background-size:32px 32px;background-size:32px 32px;border:0;-webkit-border-radius:50%;border-radius:50%;display:block;margin:0px;position:relative;height:32px;width:32px;z-index:0}.gb_Ua{background-color:#e8f0fe;border:1px solid rgba(32,33,36,.08);position:relative}.gb_Ua.gb_q{height:30px;width:30px}.gb_Ua.gb_q:hover,.gb_Ua.gb_q:active{-webkit-box-shadow:none;box-shadow:none}.gb_Va{background:#fff;border:none;-webkit-border-radius:50%;border-radius:50%;bottom:2px;-webkit-box-shadow:0px 1px 2px 0px rgba(60,64,67,.30),0px 1px 3px 1px rgba(60,64,67,.15);box-shadow:0px 1px 2px 0px rgba(60,64,67,.30),0px 1px 3px 1px rgba(60,64,67,.15);height:14px;margin:2px;position:absolute;right:0;width:14px}.gb_Wa{color:#1f71e7;font:400 22px/32px Google Sans,Roboto,Helvetica,Arial,sans-serif;text-align:center;text-transform:uppercase}@media (-webkit-min-device-pixel-ratio:1.25),(min-resolution:1.25dppx),(min-device-pixel-ratio:1.25){.gb_q::before,.gb_Xa::before{display:inline-block;-webkit-transform:scale(0.5);-webkit-transform:scale(0.5);transform:scale(0.5);-webkit-transform-origin:left 0;-webkit-transform-origin:left 0;transform-origin:left 0}.gb_D .gb_Xa::before{-webkit-transform:scale(scale(0.416666667));-webkit-transform:scale(scale(0.416666667));transform:scale(scale(0.416666667))}}.gb_q:hover,.gb_q:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15);box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_q:active{-webkit-box-shadow:inset 0 2px 0 rgba(0,0,0,.15);box-shadow:inset 0 2px 0 rgba(0,0,0,.15)}.gb_q:active::after{background:rgba(0,0,0,.1);-webkit-border-radius:50%;border-radius:50%;content:"";display:block;height:100%}.gb_Za{cursor:pointer;line-height:40px;min-width:30px;opacity:.75;overflow:hidden;vertical-align:middle;text-overflow:ellipsis}.gb_d.gb_Za{width:auto}.gb_Za:hover,.gb_Za:focus{opacity:.85}.gb_0a .gb_Za,.gb_0a .gb_1a{line-height:26px}#gb#gb.gb_0a a.gb_Za,.gb_0a .gb_1a{font-size:11px;height:auto}.gb_2a{border-top:4px solid #000;border-left:4px dashed transparent;border-right:4px dashed transparent;display:inline-block;margin-left:6px;opacity:.75;vertical-align:middle}.gb_za:hover .gb_2a{opacity:.85}.gb_xa>.gb_b{padding:3px 3px 3px 4px}.gb_3a.gb_Ta{color:#fff}.gb_B .gb_Za,.gb_B .gb_2a{opacity:1}#gb#gb.gb_B.gb_B a.gb_Za,#gb#gb .gb_B.gb_B a.gb_Za{color:#fff}.gb_B.gb_B .gb_2a{border-top-color:#fff;opacity:1}.gb_V .gb_q:hover,.gb_B .gb_q:hover,.gb_V .gb_q:focus,.gb_B .gb_q:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.2);box-shadow:0 1px 0 rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.2)}.gb_4a .gb_b,.gb_5a .gb_b{position:absolute;right:1px}.gb_b.gb_A,.gb_6a.gb_A,.gb_za.gb_A{-webkit-flex:0 1 auto;-webkit-box-flex:0;flex:0 1 auto}.gb_7a.gb_8a .gb_Za{width:30px!important}.gb_p{height:40px;position:absolute;right:-5px;top:-5px;width:40px}.gb_9a .gb_p,.gb_ab .gb_p{right:0;top:0}.gb_b .gb_d{padding:4px}.gb_s{display:none}.gb_za:not(.gb_nd){position:relative}.gb_za:not(.gb_nd)::after{content:"";border:1px solid #202124;opacity:.13;position:absolute;top:4px;left:4px;-webkit-border-radius:50%;border-radius:50%;width:30px;height:30px}.gb_xa{-webkit-box-sizing:border-box;box-sizing:border-box;cursor:pointer;display:inline-block;height:48px;overflow:hidden;outline:none;padding:7px 0 0 16px;vertical-align:middle;width:142px;-webkit-border-radius:28px;border-radius:28px;background-color:transparent;border:1px solid;position:relative}.gb_xa .gb_za{width:32px;height:32px;padding:0}.gb_Aa .gb_xa,.gb_Ba .gb_xa{border-color:#747775;border-color:var(--gm3-sys-color-outline,#747775)}.gb_Aa.gb_i .gb_xa,.gb_Ba.gb_i .gb_xa{border-color:#8e918f;border-color:var(--gm3-sys-color-outline,#8e918f)}.gb_Ca .gb_xa{border-color:#747775;border-color:var(--gm3-sys-color-outline,#747775)}.gb_Ca.gb_i .gb_xa{border-color:#e3e3e3;border-color:var(--gm3-sys-color-on-surface,#e3e3e3)}.gb_Da{display:inherit}.gb_xa .gb_Da{background:#fff;-webkit-border-radius:6px;border-radius:6px;display:inline-block;left:15px;position:initial;padding:2px;top:-1px;height:32px;-webkit-box-sizing:border-box;box-sizing:border-box;width:78px}.gb_Fa{text-align:center}.gb_Fa.gb_Ha{background-color:#f1f3f4}.gb_Fa .gb_Ia{vertical-align:middle;max-height:28px;max-width:74px}.gb_ha .gb_xa .gb_b.gb_Fd{padding:0;margin-right:9px;float:right}.gb_ha:not(.gb_Ja) .gb_xa{margin-left:10px;margin-right:4px}sentinel{}:root{--COEmY:#1f1f1f;--xhUGwc:#fff}:root{--vZe0jb:#a8c7fa;--nwXobb:#638ed4;--VuZXBd:#001d35;--uLz37c:#545d7e;--jINu6c:#001d35;--TyVYld:#0b57d0;--ZEpPmd:#c3d9fb;--QWaaaf:#638ed4;--DEeStf:#f5f8ff;--TSWZIb:#e5edff;--BRLwE:#d3e3fd;--gS5jXb:#dadce0;--Aqn7xd:#d2d2d2;--EpFNW:#fff;--IXoxUe:#5e5e5e;--bbQxAb:#474747;--YLNNHc:#1f1f1f;--TMYS9:#0b57d0;--JKqx2:#1a0dab;--rrJJUc:#0b57d0;--mXZkqc:#d2d2d2;--Nsm0ce:#0b57d0;--XKMDxc:#f3f5f6;--aYn2S:#f3f5f6;--Lm570b:#dee1e3}.IiOSLb .rsGxI.Ww4FFb,.Ww4FFb{background-color:var(--xhUGwc);border-radius:0px;border-width:0}.IiOSLb .rsGxI.Ww4FFb,.Ww4FFb{box-shadow:none}.Ww4FFb .mnr-c:not(:empty),.mnr-c:not(:empty) .Ww4FFb,.Ww4FFb .Ww4FFb{box-shadow:none;margin-bottom:0px}.vt6azd{margin:0px 0px 8px}.vt6azd{margin:0px 0px 30px}.CBvvz{margin:-var(--sds-sys-measurement--space-sm) 0px 0px}.CBvvz{margin:-30px 0px 0px}.jbBItf{display:block;position:relative}.DU0NJ{bottom:0;left:0;position:absolute;right:0;top:0}.lP3Jof{display:inline-block;position:relative}.nNMuOd{-webkit-animation:qli-container-rotate 1568.2352941176ms linear infinite;animation:qli-container-rotate 1568.2352941176ms linear infinite}@-webkit-keyframes qli-container-rotate{from{-webkit-transform:rotate(0);transform:rotate(0)}to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}}@keyframes qli-container-rotate{from{-webkit-transform:rotate(0);transform:rotate(0)}to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}}.RoKmhb{height:100%;opacity:0;position:absolute;width:100%}.nNMuOd .VQdeab{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-blue-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-blue-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.nNMuOd .IEqiAf{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-red-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-red-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.nNMuOd .smocse{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-yellow-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-yellow-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.nNMuOd .FlKbCe{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-green-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-green-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.BSnLb .nNMuOd .RoKmhb{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;opacity:0.99}@-webkit-keyframes qli-fill-unfill-rotate{0%{-webkit-transform:rotate(0);transform:rotate(0)}12.5%{-webkit-transform:rotate(135deg);transform:rotate(135deg)}25%{-webkit-transform:rotate(270deg);transform:rotate(270deg)}37.5%{-webkit-transform:rotate(405deg);transform:rotate(405deg)}50%{-webkit-transform:rotate(540deg);transform:rotate(540deg)}62.5%{-webkit-transform:rotate(675deg);transform:rotate(675deg)}75%{-webkit-transform:rotate(810deg);transform:rotate(810deg)}87.5%{-webkit-transform:rotate(945deg);transform:rotate(945deg)}100%{-webkit-transform:rotate(3turn);transform:rotate(3turn)}}@keyframes qli-fill-unfill-rotate{0%{-webkit-transform:rotate(0);transform:rotate(0)}12.5%{-webkit-transform:rotate(135deg);transform:rotate(135deg)}25%{-webkit-transform:rotate(270deg);transform:rotate(270deg)}37.5%{-webkit-transform:rotate(405deg);transform:rotate(405deg)}50%{-webkit-transform:rotate(540deg);transform:rotate(540deg)}62.5%{-webkit-transform:rotate(675deg);transform:rotate(675deg)}75%{-webkit-transform:rotate(810deg);transform:rotate(810deg)}87.5%{-webkit-transform:rotate(945deg);transform:rotate(945deg)}100%{-webkit-transform:rotate(3turn);transform:rotate(3turn)}}@-webkit-keyframes qli-blue-fade-in-out{0%{opacity:0.99}25%{opacity:0.99}26%{opacity:0}89%{opacity:0}90%{opacity:0.99}100%{opacity:0.99}}@keyframes qli-blue-fade-in-out{0%{opacity:0.99}25%{opacity:0.99}26%{opacity:0}89%{opacity:0}90%{opacity:0.99}100%{opacity:0.99}}@-webkit-keyframes qli-red-fade-in-out{0%{opacity:0}15%{opacity:0}25%{opacity:0.99}50%{opacity:0.99}51%{opacity:0}}@keyframes qli-red-fade-in-out{0%{opacity:0}15%{opacity:0}25%{opacity:0.99}50%{opacity:0.99}51%{opacity:0}}@-webkit-keyframes qli-yellow-fade-in-out{0%{opacity:0}40%{opacity:0}50%{opacity:0.99}75%{opacity:0.99}76%{opacity:0}}@keyframes qli-yellow-fade-in-out{0%{opacity:0}40%{opacity:0}50%{opacity:0.99}75%{opacity:0.99}76%{opacity:0}}@-webkit-keyframes qli-green-fade-in-out{0%{opacity:0}65%{opacity:0}75%{opacity:0.99}90%{opacity:0.99}100%{opacity:0}}@keyframes qli-green-fade-in-out{0%{opacity:0}65%{opacity:0}75%{opacity:0.99}90%{opacity:0.99}100%{opacity:0}}.beDQP{display:inline-block;height:100%;overflow:hidden;position:relative;width:50%}.FcXfi{box-sizing:border-box;height:100%;left:45%;overflow:hidden;position:absolute;top:0;width:10%}.SPKFmc{border-radius:50%;border:3px solid transparent;box-sizing:border-box}@media (forced-colors:active),(prefers-contrast:more){.beDQP:last-child .SPKFmc{border:none}}.x3SdXd{width:200%}.J7uuUe{-webkit-transform:rotate(129deg);transform:rotate(129deg)}.sDPIC{left:-100%;-webkit-transform:rotate(-129deg);transform:rotate(-129deg)}.tS3P5{left:-450%;width:1000%}.VQdeab .SPKFmc{border-color:#4285f4}.IEqiAf .SPKFmc{border-color:#ea4335}.smocse .SPKFmc{border-color:#fbbc04}.FlKbCe .SPKFmc{border-color:#34a853}.RoKmhb .J7uuUe{border-bottom-color:transparent;border-right-color:transparent}.RoKmhb .sDPIC{border-bottom-color:transparent;border-left-color:transparent}.RoKmhb .tS3P5{border-bottom-color:transparent}.GgTJWe .nNMuOd .J7uuUe{-webkit-animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both}.GgTJWe .nNMuOd .sDPIC{-webkit-animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both}.BSnLb .nNMuOd .J7uuUe{-webkit-animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;border-left-color:var(--EpFNW);border-top-color:var(--EpFNW)}.BSnLb .nNMuOd .sDPIC{-webkit-animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;border-right-color:var(--EpFNW);border-top-color:var(--EpFNW)}.BSnLb .nNMuOd .tS3P5{border-color:var(--EpFNW);border-bottom-color:transparent}@-webkit-keyframes qli-left-spin{0%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}50%{-webkit-transform:rotate(-5deg);transform:rotate(-5deg)}100%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}}@keyframes qli-left-spin{0%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}50%{-webkit-transform:rotate(-5deg);transform:rotate(-5deg)}100%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}}@-webkit-keyframes qli-right-spin{0%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}50%{-webkit-transform:rotate(5deg);transform:rotate(5deg)}100%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}}@keyframes qli-right-spin{0%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}50%{-webkit-transform:rotate(5deg);transform:rotate(5deg)}100%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}}.OhScic{margin:0px}.zsYMMe{padding:0px}.bNg8Rb{clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;user-select:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none}.TBC9ub{margin-left:0px;margin-right:0px}.OZ5bRd{margin-bottom:auto;margin-top:auto}.wgbRNb{cursor:pointer;height:72px;position:absolute;display:block;visibility:inherit;width:36px;bottom:0;opacity:.8;top:0;z-index:101}.wgbRNb.tHT0l{-webkit-transition:opacity .5s,visibility .5s;transition:opacity .5s,visibility .5s}.wgbRNb:hover{opacity:.9}.wgbRNb.pQXcHc,.wgbRNb.pQXcHc:hover{cursor:default;opacity:0;visibility:hidden}.b5K9zd{bottom:0;display:block;position:absolute!important;top:0}.wgbRNb.ENJHPd:hover g-fab{color:#202124!important}.bCwlI.ENJHPd g-fab,.VdehBf.ENJHPd g-fab{box-shadow:0 7px 15px rgba(0,0,0,0.2)}.wgbRNb.ENJHPd{height:50px;width:50px;opacity:1}.wgbRNb.ENJHPd.pQXcHc,.wgbRNb.ENJHPd.pQXcHc:hover{opacity:0}.bCwlI.ENJHPd g-fab,.VdehBf.ENJHPd g-fab{cursor:pointer;height:50px;width:50px}.bCwlI.ENJHPd{left:-25px}.VdehBf.ENJHPd{right:-25px}.wgbRNb.HEeAqe:hover g-fab{color:#202124!important}.wgbRNb.HEeAqe{height:48px;width:48px;opacity:.9}.wgbRNb.HEeAqe:hover{opacity:1}.wgbRNb.HEeAqe.pQXcHc,.wgbRNb.HEeAqe.pQXcHc:hover{opacity:0}.bCwlI.HEeAqe g-fab,.VdehBf.HEeAqe g-fab{box-shadow:0 7px 15px rgba(0,0,0,0.2);cursor:pointer;height:48px;width:48px}.bCwlI.HEeAqe{left:20px}.VdehBf.HEeAqe{right:20px}.wgbRNb.TVgFVb:hover g-fab{color:#202124!important}.wgbRNb.TVgFVb{height:40px;width:40px}.bCwlI.TVgFVb g-fab,.VdehBf.TVgFVb g-fab{box-shadow:0 4px 4px rgba(0,0,0,0.3),0 0 4px rgba(0,0,0,0.2);cursor:pointer}.bCwlI.TVgFVb{left:-58px}.VdehBf.TVgFVb{right:-58px}.bCwlI.Yze26d .vWtmKf,.VdehBf.Yze26d .PFY4o{background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAwAAAAuCAYAAAAcEfjaAAABV0lEQVRIx+2VsW7CQBBEDwTpIkXICMuyJdtfQsGXQUVFlSpVmjTESOn4BAoXLigsueAvaM2MBAht7g6v06ZYwNK8893ezGLatjV5ni9QO2PMC599ZdI0nWdZdgbQ4vsH0NgLQLSn+FZ4/gY0cgJBELxCdHiEUF+AhlaAH9jWG0SleNOnDbr/iON4AlEloA9AAyvAiqIogPAooHcnwIJghqrFmTZOgJUkSQRRI6C1E7huL8GbTmJ7Ky2w/PuWVIcOw3Daua2qi1NZQ20+i723XnurA/QQ0aJTRJ8J/oEuAFvNqcjWPwV4ibzM66Weeck+8YhTUNhm7xIPaUAhPtCoVjGtLdxbMgK/zsCwMDRi5YrhsnaJcRQrHzkNrW1l0MXKNQeCy95rsXLDUeNK3EqsfOIQ8/0DLVWAeku9Du1rK6ehE1BfnNoavcwn7L3tZO9eARIRLW4RvQA0+6DNwTHW6QAAAABJRU5ErkJggg==);background-repeat:no-repeat;height:20px;opacity:.56;width:12px}.bCwlI.Yze26d,.VdehBf.Yze26d{opacity:.9;width:80px}.bCwlI.Yze26d .vWtmKf{background-position:0 -26px;left:2px}.VdehBf.Yze26d .PFY4o{background-position:0 0;right:2px}.bCwlI.Yze26d{background:linear-gradient(90deg,#fff 50%,rgba(255,255,255,.09) 100%);left:0}.VdehBf.Yze26d{background:linear-gradient(270deg,#fff 50%,rgba(255,255,255,.09) 100%);right:0}.wgbRNb.T9Wh5:hover g-fab{color:#202124!important;box-shadow:0 0 0 1px rgba(0,0,0,0.04),0 4px 8px 0 rgba(0,0,0,0.2)}.wgbRNb.T9Wh5{height:36px;width:36px;opacity:1}.wgbRNb.T9Wh5.pQXcHc,.wgbRNb.T9Wh5.pQXcHc:hover{opacity:0}.bCwlI.T9Wh5 g-fab,.VdehBf.T9Wh5 g-fab{cursor:pointer;height:36px;width:36px}.bCwlI.T9Wh5{left:-18px}.VdehBf.T9Wh5{right:-18px}.bCwlI.SL0Gp .vWtmKf,.VdehBf.SL0Gp .PFY4o{background-repeat:no-repeat;opacity:.54;width:24px}.bCwlI.SL0Gp .vWtmKf{background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAQAAABKfvVzAAAAQ0lEQVR4AWNABaNAAQhJUv4ACGVJUf6f4TADDw2VHyFN+VEGXmJdfwCo/AeDNIhJqQ2E/UBLLYiApVFMI9ISWWAUAAAy1x3G3j1wxQAAAABJRU5ErkJggg==)}.VdehBf.SL0Gp .PFY4o{background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAQAAABKfvVzAAAAUElEQVR4AWOAgFHAAYQkKd8BhCRoUWZ4wfCfNC1aDC/poEWb4RWpWnQYfgK1bCBWOSPDFKDyHwwexCqfTFPlkyDKiQ/SH2DlJAAPIKQIjAIADAMd5ce1j0IAAAAASUVORK5CYII=)}.VdehBf.SL0Gp,.bCwlI.SL0Gp{width:24px}.wgbRNb.SL0Gp.pQXcHc,.wgbRNb.SL0Gp.pQXcHc:hover{cursor:default;opacity:1;visibility:inherit}.wgbRNb.SL0Gp.pQXcHc .vWtmKf,.wgbRNb.SL0Gp.pQXcHc .PFY4o{opacity:.2}.wgbRNb.SL0Gp{height:24px;margin:0}.wgbRNb.SL0Gp:hover{opacity:1}.wgbRNb.zfpUke:hover g-fab{color:#202124!important}.wgbRNb.zfpUke{height:36px;width:36px;opacity:0}.z1Mm0e:hover .wgbRNb.zfpUke{opacity:.9}.z1Mm0e .wgbRNb.zfpUke:hover,.z1Mm0e .wgbRNb.zfpUke:focus-visible{opacity:1}.wgbRNb.zfpUke.pQXcHc,.wgbRNb.zfpUke.pQXcHc:hover{opacity:0}.bCwlI.zfpUke g-fab,.VdehBf.zfpUke g-fab{box-shadow:0 0 0 1px rgba(0,0,0,0.04),0 4px 8px 0 rgba(0,0,0,0.2);cursor:pointer;height:36px;width:36px}.bCwlI.zfpUke{left:16px}.VdehBf.zfpUke{right:16px}.bCwlI.ENpXyb .vWtmKf,.VdehBf.ENpXyb .PFY4o{background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAwAAAAuCAYAAAAcEfjaAAABV0lEQVRIx+2VsW7CQBBEDwTpIkXICMuyJdtfQsGXQUVFlSpVmjTESOn4BAoXLigsueAvaM2MBAht7g6v06ZYwNK8893ezGLatjV5ni9QO2PMC599ZdI0nWdZdgbQ4vsH0NgLQLSn+FZ4/gY0cgJBELxCdHiEUF+AhlaAH9jWG0SleNOnDbr/iON4AlEloA9AAyvAiqIogPAooHcnwIJghqrFmTZOgJUkSQRRI6C1E7huL8GbTmJ7Ky2w/PuWVIcOw3Daua2qi1NZQ20+i723XnurA/QQ0aJTRJ8J/oEuAFvNqcjWPwV4ibzM66Weeck+8YhTUNhm7xIPaUAhPtCoVjGtLdxbMgK/zsCwMDRi5YrhsnaJcRQrHzkNrW1l0MXKNQeCy95rsXLDUeNK3EqsfOIQ8/0DLVWAeku9Du1rK6ehE1BfnNoavcwn7L3tZO9eARIRLW4RvQA0+6DNwTHW6QAAAABJRU5ErkJggg==);background-repeat:no-repeat;height:20px;width:12px}.bCwlI.ENpXyb .vWtmKf{background-position:0 -26px;left:8px}.VdehBf.ENpXyb .PFY4o{background-position:0 0;right:8px}.bCwlI.ENpXyb{left:0}.VdehBf.ENpXyb{right:0}.bCwlI.ENpXyb{border-bottom-right-radius:36px;border-top-right-radius:36px;box-shadow:1px 0 2px rgba(0,0,0,0.5)}.VdehBf.ENpXyb{border-bottom-left-radius:36px;border-top-left-radius:36px;box-shadow:-1px 0 2px rgba(0,0,0,0.5)}.bCwlI.AoT6sc .vWtmKf{left:2px}.VdehBf.AoT6sc .PFY4o{right:2px}.bCwlI.AoT6sc{left:-32px;border:1px solid #f8f9fa;border-radius:2px 0 0 2px}.VdehBf.AoT6sc{right:-32px;border:1px solid #f8f9fa;border-radius:0 2px 2px 0}.wgbRNb.AoT6sc{background-image:-webkit-gradient(linear,left top,left bottom,from(#f8f9fa),to(#f8f9fa));background-image:-webkit-linear-gradient(top,#f8f9fa,#f8f9fa);background-image:linear-gradient(top,#f8f9fa,#f8f9fa);height:50px;width:30px}.wgbRNb.AoT6sc:hover{background-image:-webkit-gradient(linear,left top,left bottom,from(#f8f9fa),to(#f8f9fa));background-image:-webkit-linear-gradient(top,#f8f9fa,#f8f9fa);background-image:linear-gradient(top,#f8f9fa,#f8f9fa)}.wgbRNb.btpNFe:hover g-fab{color:#202124!important}.wgbRNb.btpNFe{height:36px;width:36px;opacity:.9}.wgbRNb.btpNFe:hover{opacity:1}.wgbRNb.btpNFe.pQXcHc,.wgbRNb.btpNFe.pQXcHc:hover{opacity:0}.bCwlI.btpNFe g-fab,.VdehBf.btpNFe g-fab{box-shadow:0 0 0 1px rgba(0,0,0,0.04),0 4px 8px 0 rgba(0,0,0,0.2);cursor:pointer;height:36px;width:36px}.bCwlI.btpNFe{left:-18px}.VdehBf.btpNFe{right:-18px}.wgbRNb.jSZMre:hover g-fab{color:#202124!important}.wgbRNb.jSZMre{height:32px;width:32px;opacity:.9;padding:8px}.wgbRNb.jSZMre:hover{opacity:1}.wgbRNb.jSZMre.pQXcHc,.wgbRNb.jSZMre.pQXcHc:hover{opacity:0}.bCwlI.jSZMre g-fab,.VdehBf.jSZMre g-fab{box-shadow:0 7px 15px rgba(0,0,0,0.2);cursor:pointer;height:32px;width:32px}.bCwlI.jSZMre{left:20px}.VdehBf.jSZMre{right:20px}.wgbRNb.vkcLib{height:40px;width:40px;opacity:0}.z1Mm0e:hover .wgbRNb.vkcLib,.z1Mm0e .wgbRNb.vkcLib:hover,.z1Mm0e .wgbRNb.vkcLib:focus-visible{opacity:1}.wgbRNb.vkcLib.pQXcHc,.wgbRNb.vkcLib.pQXcHc:hover{opacity:0}.bCwlI.vkcLib g-fab,.VdehBf.vkcLib g-fab{box-shadow:0 0 0 1px rgba(0,0,0,0.04),0 4px 8px 0 rgba(0,0,0,0.2);cursor:pointer;height:24px;width:24px;position:relative;top:8px;left:8px}.bCwlI.vkcLib{left:4px}.VdehBf.vkcLib{right:4px}.OvQkSb{border-radius:9999px}.S3PB2d{margin:auto}.sr9hec{display:block;position:relative;z-index:0}.sr9hec{cursor:pointer}.sr9hec{border:1px solid #dadce0}.sr9hec:focus{outline:none}.sr9hec .U8v51e{position:absolute;left:0;right:0;top:0;bottom:0;width:24px;height:24px}.s3IB3{width:40px;height:40px}.a11Pr{width:56px;height:56px}.MKCV1b{width:28px;height:28px}.sr9hec.MKCV1b .U8v51e{width:22px;height:22px}.OZQDWd{width:18px;height:18px}.sr9hec.OZQDWd .U8v51e{width:12px;height:12px}.e5KZJf{display:none;position:absolute;width:100%;height:100%;opacity:.1;left:0;top:0}.e5KZJf:active{-webkit-animation-duration:.4s;animation-duration:.4s;-webkit-animation-name:shift;animation-name:shift}@-webkit-keyframes shift{25%{background:#1f1f1f}}@keyframes shift{25%{background:#1f1f1f}}.Xx7Mif{contain:style;position:relative}.E5eFb{width:100%;contain:size style}.LoygGf{width:100%;display:block}.CTOaxb{position:fixed;top:0;left:0;contain:size layout style}.OMqmfd{position:-webkit-sticky;position:sticky;top:0}.zLSRge{border-bottom:1px solid var(--gS5jXb)}.AX1Qf{position:absolute;left:50vw;width:1px;height:2px;visibility:hidden;pointer-events:none}.KLEmSd{border-bottom:1px solid #dadce0}.v0rrvd{padding-bottom:16px}.GUHazd{padding-bottom:12px}.bvSTKc{padding:8px}.cB4NFc{padding-top:16px}.OdBhM{padding-top:8px}.wok5vf{padding:24px}@media (min-height:576px){.uSolm .qk7LXc{height:100%}.mcPPZ.uSolm{padding:64px 0px}.qk7LXc.uSolm{height:calc(100% - 128px)}}@media (max-height:575px){.uSolm .qk7LXc,.qk7LXc.uSolm{height:100%;max-height:448px}}@media (min-height:496px){.GeOznc .qk7LXc{height:100%}.mcPPZ.GeOznc{padding:24px 0px}.qk7LXc.GeOznc{height:calc(100% - 48px)}}@media (max-height:495px){.GeOznc .qk7LXc,.qk7LXc.GeOznc{height:100%;max-height:448px}}.TUOsUe{text-align:left}.KUf18.ivkdbf{background-color:rgba(0,0,0,0.6);opacity:1;visibility:inherit}.VfsLpf.ivkdbf{background-color:#000;opacity:.4;visibility:inherit}.J3Hnlf.ivkdbf{background-color:#202124;opacity:.7;visibility:inherit}.X46m8.ivkdbf{background-color:#000;opacity:.8;visibility:inherit}.cBoDed.ivkdbf{background-color:#f8f9fa;opacity:.85;visibility:inherit}.kyk7qb.ivkdbf{background-color:#202124;opacity:.6;visibility:inherit}.qk7LXc.ivkdbf{opacity:1}.mcPPZ.ivkdbf{opacity:1;visibility:inherit}.mcPPZ.nP0TDe{cursor:pointer}.mcPPZ.nP0TDe .qk7LXc{cursor:default}.kJFf0c{position:fixed;z-index:9997;right:0;bottom:-200px;top:0;left:0;-webkit-transition:opacity .25s;transition:opacity .25s;opacity:0;visibility:hidden}.qk7LXc{display:inline-block;z-index:9997;background-color:#fff;opacity:0;white-space:normal;overflow:hidden}.qk7LXc{border-radius:8px}.qk7LXc{box-shadow:0px 5px 26px 0px rgba(0,0,0,0.22),0px 20px 28px 0px rgba(0,0,0,0.3)}.qk7LXc.DJEOfc{background-color:transparent}.qk7LXc.DJEOfc{box-shadow:none}.qk7LXc.Fb1AKc{position:relative;vertical-align:middle}.qk7LXc.By9mMc{position:fixed}.qk7LXc.W6Z5of{top:50%;left:50%;-webkit-transform:translate(-50%,-50%);transform:translate(-50%,-50%)}.qk7LXc.ulWzbd{position:absolute}.qk7LXc.P1WYLb{border:1px solid var(--mXZkqc);box-shadow:#dadce0}.mcPPZ{position:fixed;right:0;bottom:0;top:0;left:0;z-index:9997;vertical-align:middle;visibility:hidden;white-space:nowrap;max-height:100%;max-width:100%;overflow-x:hidden;overflow-y:auto}.mcPPZ.xg7rAe{text-align:center}.mcPPZ::after{content:"";display:inline-block;height:100%;vertical-align:middle}.LjfRsf{height:0;opacity:0;position:absolute;width:0}.VH47ed{visibility:hidden}.TaoyYc{overflow:hidden}.TaoyYc{position:fixed;width:100%}.qk7LXc.aJPx6e{overflow:visible}.vAJJzd{opacity:.999}.yMNJR .qk7LXc,.qk7LXc.yMNJR{max-width:100%}.cJFqsd .qk7LXc,.qk7LXc.cJFqsd{height:100%}.rfx2Y .qk7LXc,.qk7LXc.rfx2Y{width:100%}.BhUHze .qk7LXc,.qk7LXc.BhUHze{width:75%}.dgVGnc .qk7LXc,.qk7LXc.dgVGnc{width:90%}.GmoL0c{margin-right:12px}.xTWltf{margin-right:24px}.Wt5Tfe{padding-left:0px;padding-right:0px}.eJtrMc{padding-bottom:8px;padding-top:8px}.VDgVie{text-align:center}.SlP8xc{text-transform:none}.MTIaKb,.LwDUdc,.FAoEle,.RlTCPd,.wPNfjb,.caNvfd,.Vnob4b,.bbxTBb,.DpgmK,.YKUhfb,.uNnvb,.aVsZpf,.RoOVmf,.dIfvQd,.V3Ezn,.Enb9pe,.mYuoaf,.kJSB8,.tUr4Kc,.iQMtqe{--Yi4Nb:var(--mXZkqc);--pEa0Bc:var(--bbQxAb);--kloG3:var(--mXZkqc);--YaIeMb:var(--XKMDxc);--Pa8Wlb:var(--Nsm0ce);--izGsqb:var(--Nsm0ce);--todMNcl:var(--EpFNW);--p9J9c:var(--Nsm0ce)}:root{--KIZPne:#a3c9ff;--xPpiM:#001d35;--Ehh4mf:var(--Nsm0ce)}:root{--Yi4Nb:#d2d2d2;--pEa0Bc:#474747;--kloG3:#d2d2d2;--YaIeMb:#f7f8f9;--Pa8Wlb:#0b57d0;--izGsqb:#0b57d0;--todMNcl:#fff;--p9J9c:#0b57d0}.k0Jjg,.brKmxb:focus-visible{outline:0}.k0Jjg:focus-visible .niO4u,.brKmxb:focus-visible .niO4u{outline:2px solid var(--Pa8Wlb);outline-offset:1px}.niO4u{-webkit-box-align:center;-webkit-align-items:center;align-items:center;box-sizing:border-box;cursor:pointer;display:inline-block;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;margin-left:auto;margin-right:auto;position:relative;width:100%}.gzV1t .niO4u{-webkit-box-align:stretch;-webkit-align-items:stretch;align-items:stretch;display:-webkit-box;display:-webkit-flex;display:flex}.niO4u::before{content:"";height:48px;left:0;margin-top:-24px;margin-left:-1px;margin-right:-1px;position:absolute;right:0;top:50%}.kHtcsd{border:none;border-radius:inherit;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-align:center;-webkit-align-items:center;align-items:center;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;width:100%}.DopHqc{height:100%}.d3o3Ad,.clOx1e,.WoA9Zd{display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-align:center;-webkit-align-items:center;align-items:center}.QuU3Wb{margin-top:6px}.clOx1e{margin:5px 16px}.eFSWxd .clOx1e{margin-left:8px}.eFSWxd .d3o3Ad,.R04TOd{margin-left:12px}.A29zgf{border-radius:8px;display:inline-block;vertical-align:middle}.A29zgf .niO4u{border-radius:8px}.A29zgf .kHtcsd{border-radius:7px}.pAn7ne{white-space:nowrap;overflow:hidden;text-overflow:ellipsis}.gjcKCc{-webkit-tap-highlight-color:transparent}.niO4u{-webkit-transition:background-color .25s linear;transition:background-color .25s linear}.btku5b{-webkit-transition:color .25s linear;transition:color .25s linear}a.gjcKCc:focus-visible{color:#1967d2}a.gjcKCc:focus-visible .niO4u{background-color:#e8f0fe;}.fCrZyc{display:inline-block;vertical-align:middle}.fCrZyc .niO4u{border-radius:9999px}.LwdV0e.OJeuxf .iCQO5d{width:36px}.gUAcff.OJeuxf .iCQO5d{width:32px}.NQYJvc.OJeuxf .iCQO5d{width:44px}.OJeuxf .niO4u::before{width:48px;margin-left:-24px;left:50%}.LwdV0e .y1Cbob.vGnXdb.vGnXdb{height:48px;padding:0 4px}.k1U36b{font-size:12px;font-family:Arial,sans-serif-medium,sans-serif;font-weight:500;line-height:16px}.UZXANc.gUAcff .niO4u{top:3px;height:0}.mKjEAd.gUAcff .niO4u{height:0}.bacHod.gUAcff .R04TOd,.bacHod.gUAcff .d3o3Ad{height:14px}.gUAcff.PrjL8c .niO4u{height:32px}.gUAcff.gzV1t .niO4u{min-height:32px}.gUAcff .clOx1e{line-height:16px}.gUAcff .R04TOd,.gUAcff .d3o3Ad,.gUAcff .WoA9Zd{height:16px}.UZXANc.UZXANc.LwdV0e .niO4u{top:3px;height:0}.mKjEAd.mKjEAd.LwdV0e .niO4u{height:0}.bacHod.LwdV0e .R04TOd,.bacHod.LwdV0e .d3o3Ad{height:16px}.LwdV0e.gzV1t .niO4u{min-height:36px}.LwdV0e.PrjL8c .niO4u{height:36px}.LwdV0e .R04TOd,.LwdV0e .d3o3Ad,.LwdV0e .WoA9Zd{height:18px}.NQYJvc.gzV1t .niO4u{min-height:44px}.NQYJvc.PrjL8c .niO4u{height:44px}.NQYJvc .d3o3Ad,.NQYJvc .R04TOd{border-radius:4px;overflow:hidden}.NQYJvc .d3o3Ad,.NQYJvc .R04TOd,.NQYJvc .WoA9Zd{height:20px}.FR7ZSc{color:var(--rrJJUc)}.FR7ZSc .niO4u{background-color:transparent;border:1px solid var(--Yi4Nb)}.FR7ZSc:not([selected]):not([disabled]) .d3o3Ad{color:#0b57d0}.FR7ZSc .k0Jjg:hover .niO4u,.FR7ZSc.k0Jjg:hover .niO4u{color:var(--jINu6c)}.FR7ZSc:not([selected]) .k0Jjg:hover .d3o3Ad,.FR7ZSc.k0Jjg:not([selected]):hover .d3o3Ad{color:var(--jINu6c)}.FR7ZSc .k0Jjg:hover .kHtcsd,.FR7ZSc.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:active .FR7ZSc .niO4u,.brKmxb:focus-visible .FR7ZSc .niO4u,.FR7ZSc.k0Jjg:active .niO4u,.FR7ZSc .k0Jjg:active .niO4u,.FR7ZSc.k0Jjg:focus-visible .niO4u,.FR7ZSc .k0Jjg:focus-visible .niO4u{color:var(--jINu6c)}.brKmxb:focus-visible .FR7ZSc:not([selected]):not([disabled]) .d3o3Ad,.FR7ZSc:not([selected]):not([disabled]) .k0Jjg:focus-visible .d3o3Ad,.FR7ZSc.k0Jjg:not([selected]):not([disabled]):focus-visible .d3o3Ad{color:#001d35}.brKmxb:focus-visible .FR7ZSc .kHtcsd,.FR7ZSc .k0Jjg:focus-visible .kHtcsd,.FR7ZSc.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .FR7ZSc:not([selected]):not([disabled]) .d3o3Ad,.FR7ZSc:not([selected]):not([disabled]) .k0Jjg:active .d3o3Ad,.FR7ZSc.k0Jjg:not([selected]):not([disabled]):active .d3o3Ad{color:var(--IXoxUe)}.brKmxb:active .FR7ZSc .kHtcsd,.FR7ZSc .k0Jjg:active .kHtcsd,.FR7ZSc.k0Jjg:active .kHtcsd{background-color:#0b57d039}.expUPd{color:var(--todMNcl)}.expUPd .niO4u{background-color:var(--izGsqb)}.expUPd.k0Jjg:hover .kHtcsd,.expUPd .k0Jjg:hover .kHtcsd{background-color:#001d3539}.brKmxb:focus-visible .expUPd .kHtcsd,.expUPd.k0Jjg:focus-visible .kHtcsd,.expUPd .k0Jjg:focus-visible .kHtcsd{background-color:#001d3533}.brKmxb:active .expUPd .kHtcsd,.expUPd .k0Jjg:active .kHtcsd,.expUPd.k0Jjg:active .kHtcsd{background-color:#001d3566}@media (prefers-contrast:more){.expUPd .niO4u{outline:1px solid #1f1f1f}}.zqrO0{color:var(--bbQxAb)}.zqrO0 .niO4u{background-color:var(--xhUGwc);border:1px solid var(--mXZkqc)}.brKmxb:active .zqrO0,.brKmxb:focus-visible .zqrO0,.zqrO0 .k0Jjg:hover,.zqrO0 .k0Jjg:active,.zqrO0 .k0Jjg:focus-visible,.zqrO0.k0Jjg:hover,.zqrO0.k0Jjg:focus-visible,.zqrO0.k0Jjg:active{color:var(--bbQxAb)}.zqrO0 .k0Jjg:hover .kHtcsd,.zqrO0.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:focus-visible .zqrO0 .kHtcsd,.zqrO0 .k0Jjg:focus-visible .kHtcsd,.zqrO0.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .zqrO0 .kHtcsd,.zqrO0 .k0Jjg:active .kHtcsd,.zqrO0.k0Jjg:active .kHtcsd{background-color:#0b57d039}.xab99e .niO4u{z-index:2}.xab99e .niO4u{background-color:var(--xhUGwc);border:1px solid var(--mXZkqc)}.NQYJvc.PrjL8c .niO4u{height:40px}.NQYJvc.OJeuxf .iCQO5d{width:40px}.xab99e.k0Jjg:hover .kHtcsd,.xab99e .k0Jjg:hover .kHtcsd{border:0;box-shadow:0px 4px 12px rgba(60,64,67,0.24)}.NtaMpb{color:var(--bbQxAb)}.NtaMpb .niO4u{background-color:var(--xhUGwc)}.NtaMpb .k0Jjg:hover .kHtcsd,.NtaMpb.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:focus-visible .NtaMpb .kHtcsd,.NtaMpb .k0Jjg:focus-visible .kHtcsd,.NtaMpb.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .NtaMpb .kHtcsd,.NtaMpb .k0Jjg:active .kHtcsd,.NtaMpb.k0Jjg:active .kHtcsd{background-color:#0b57d039}.Bmegof{color:#001d35}.Bmegof .niO4u{background-color:#d3e3fd}.Bmegof .k0Jjg:hover .kHtcsd,.Bmegof.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:focus-visible .Bmegof .kHtcsd,.Bmegof .k0Jjg:focus-visible .kHtcsd,.Bmegof.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .Bmegof .kHtcsd,.Bmegof .k0Jjg:active .kHtcsd,.Bmegof.k0Jjg:active .kHtcsd{background-color:#0b57d039}.r69FZ{color:#001d35}.r69FZ .niO4u{background-color:#ebf1ff}@media (prefers-contrast:more){.cD6kyf .niO4u{outline:1px solid #1f1f1f}}.r69FZ .k0Jjg:hover .kHtcsd,.r69FZ.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:focus-visible .r69FZ .kHtcsd,.r69FZ .k0Jjg:focus-visible .kHtcsd,.r69FZ.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .r69FZ .kHtcsd,.r69FZ .k0Jjg:active .kHtcsd,.r69FZ.k0Jjg:active .kHtcsd{background-color:#0b57d039}.rXoM2c{color:#5e5e5e}.rXoM2c .niO4u{background-color:var(--XKMDxc)}.rXoM2c:not([disabled]) .k0Jjg:hover .kHtcsd,.rXoM2c.k0Jjg:not([disabled]):hover .kHtcsd{background-color:rgba(31,31,31,0.08);color:var(--YLNNHc)}.brKmxb:focus-visible .rXoM2c:not([disabled]) .kHtcsd,.rXoM2c:not([disabled]) .k0Jjg:focus-visible .kHtcsd,.rXoM2c.k0Jjg:not([disabled]):focus-visible .kHtcsd{background-color:rgba(31,31,31,0.078431375)}.brKmxb:active .rXoM2c:not([disabled]) .kHtcsd,.rXoM2c:not([disabled]) .k0Jjg:active .kHtcsd,.rXoM2c.k0Jjg:active:not([disabled]) .kHtcsd{background-color:rgba(31,31,31,0.23921569);color:var(--YLNNHc)}.jdOrZc{color:var(--rrJJUc)}.jdOrZc .niO4u{background-color:transparent}.zqrO0 .k0Jjg:hover .kHtcsd,.zqrO0.k0Jjg:hover .niO4u{color:var(--jINu6c)}.jdOrZc .k0Jjg:hover .kHtcsd,.jdOrZc.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:active .jdOrZc .niO4u,.brKmxb:focus-visible .jdOrZc .niO4u,.zqrO0 .k0Jjg:active .niO4u,.zqrO0 .k0Jjg:focus-visible .niO4u,.zqrO0.k0Jjg:active .niO4u,.zqrO0.k0Jjg:focus-visible .niO4u{color:var(--jINu6c)}.brKmxb:focus-visible .jdOrZc .kHtcsd,.jdOrZc .k0Jjg:focus-visible .kHtcsd,.jdOrZc.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .jdOrZc .kHtcsd,.jdOrZc .k0Jjg:active .kHtcsd,.jdOrZc.k0Jjg:active .kHtcsd{background-color:#0b57d039}.ogBxF{color:var(--JKqx2)}.ogBxF .niO4u{background-color:transparent;border:1px solid var(--mXZkqc)}.ogBxF .k0Jjg:hover .kHtcsd,.ogBxF.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:focus-visible .ogBxF .kHtcsd,.ogBxF .k0Jjg:focus-visible .kHtcsd,.ogBxF.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .ogBxF .kHtcsd,.ogBxF .k0Jjg:active .kHtcsd,.ogBxF.k0Jjg:active .kHtcsd{background-color:#0b57d039}.x2GJWb{color:#1f1f1f}.x2GJWb .QuU3Wb{color:#1f1f1f;}.x2GJWb .niO4u{background-color:#f1f3f4}a.LcmtUb{-webkit-tap-highlight-color:transparent}a.LcmtUb:focus-visible{outline:none}a.LcmtUb:focus-visible .x2GJWb .niO4u{outline:2px solid var(--rrJJUc);outline-offset:2px}.x2GJWb:active .kHtcsd{background-color:rgba(32,33,36,0.24)}.x2GJWb .k0Jjg:hover .kHtcsd,.x2GJWb.k0Jjg:hover .kHtcsd{background-color:#0b57d015}.brKmxb:focus-visible .x2GJWb .kHtcsd,.x2GJWb .k0Jjg:focus-visible .kHtcsd,.x2GJWb.k0Jjg:focus-visible .kHtcsd{background-color:#0b57d015}.brKmxb:active .x2GJWb .kHtcsd,.x2GJWb .k0Jjg:active .kHtcsd,.x2GJWb.k0Jjg:active .kHtcsd{background-color:#0b57d039}.fXVarf{color:#fff}.fXVarf .niO4u{background-color:rgba(0,0,0,0.6)}.fXVarf .k0Jjg:hover .kHtcsd,.fXVarf.k0Jjg:hover .kHtcsd{background-color:#1f1f1f33}.brKmxb:focus-visible .fXVarf .kHtcsd,.fXVarf .k0Jjg:focus-visible .kHtcsd,.fXVarf.k0Jjg:focus-visible .kHtcsd{background-color:#1f1f1f33}.brKmxb:active .fXVarf .kHtcsd,.fXVarf .k0Jjg:active .kHtcsd,.fXVarf.k0Jjg:active .kHtcsd{background-color:#1f1f1f66}.W68A0[selected]{color:var(--xPpiM)}.W68A0[selected] .niO4u{background-color:var(--KIZPne);border-color:transparent}.W68A0[selected] .k0Jjg:hover .kHtcsd,.W68A0.k0Jjg[selected]:hover .kHtcsd{background-color:#d2e3fc}.r69FZ .d3o3Ad,.r69FZ .WoA9Zd{color:#0b57d0}.r69FZ:not([disabled]) .k0Jjg:hover .d3o3Ad,.r69FZ:not([disabled]) .k0Jjg:hover .WoA9Zd,.r69FZ.k0Jjg:not([disabled]):hover .d3o3Ad,.r69FZ.k0Jjg:not([disabled]):hover .WoA9Zd{color:#001d35}.brKmxb:focus-visible .r69FZ:not([disabled]) .d3o3Ad,.brKmxb:focus-visible .r69FZ:not([disabled]) .WoA9Zd,.brKmxb:active .r69FZ:not([disabled]) .d3o3Ad,.brKmxb:active .r69FZ:not([disabled]) .WoA9Zd,.r69FZ:not([disabled]) .k0Jjg:focus-visible .d3o3Ad,.r69FZ:not([disabled]) .k0Jjg:focus-visible .WoA9Zd,.r69FZ:not([disabled]) .k0Jjg:active .d3o3Ad,.r69FZ:not([disabled]) .k0Jjg:active .WoA9Zd,.r69FZ.k0Jjg:not([disabled]):focus-visible .d3o3Ad,.r69FZ.k0Jjg:not([disabled]):focus-visible .WoA9Zd,.r69FZ.k0Jjg:not([disabled]):active .d3o3Ad,.r69FZ.k0Jjg:not([disabled]):active .WoA9Zd{color:#001d35}.Bmegof .d3o3Ad,.Bmegof .WoA9Zd{color:#0b57d0}.Bmegof:not([disabled]) .k0Jjg:hover .d3o3Ad,.Bmegof:not([disabled]) .k0Jjg:hover .WoA9Zd,.Bmegof.k0Jjg:not([disabled]):hover .d3o3Ad,.Bmegof.k0Jjg:not([disabled]):hover .WoA9Zd{color:#001d35}.brKmxb:focus-visible .Bmegof:not([disabled]) .d3o3Ad,.brKmxb:focus-visible .Bmegof:not([disabled]) .WoA9Zd,.brKmxb:active .Bmegof:not([disabled]) .d3o3Ad,.brKmxb:active .Bmegof:not([disabled]) .WoA9Zd,.Bmegof:not([disabled]) .k0Jjg:focus-visible .d3o3Ad,.Bmegof:not([disabled]) .k0Jjg:focus-visible .WoA9Zd,.Bmegof:not([disabled]) .k0Jjg:active .d3o3Ad,.Bmegof:not([disabled]) .k0Jjg:active .WoA9Zd,.Bmegof.k0Jjg:not([disabled]):focus-visible .d3o3Ad,.Bmegof.k0Jjg:not([disabled]):focus-visible .WoA9Zd,.Bmegof.k0Jjg:not([disabled]):active .d3o3Ad,.Bmegof.k0Jjg:not([disabled]):active .WoA9Zd{color:#001d35}.sLl7de[selected]{color:var(--xPpiM)}.sLl7de[selected] .niO4u{background-color:var(--KIZPne);border-color:transparent}.sLl7de.rlt7Ub[selected] .d3o3Ad,.sLl7de.eFSWxd[selected] .d3o3Ad{display:none}.sLl7de[selected] .R04TOd{display:-webkit-box;display:-webkit-flex;display:flex}.sLl7de.LwdV0e[selected] .clOx1e:not(.l6PAOd){margin-left:8px}.sLl7de[selected] .k0Jjg:hover .kHtcsd,.sLl7de.k0Jjg[selected]:hover .kHtcsd{background-color:#d2e3fc}.d2D5h[selected]{color:var(--rrJJUc)}.d2D5h[selected] .niO4u{background-color:var(--xhUGwc)}.d2D5h.rlt7Ub[selected] .d3o3Ad,.d2D5h.eFSWxd[selected] .d3o3Ad{display:none}.d2D5h[selected] .R04TOd{display:-webkit-box;display:-webkit-flex;display:flex}.d2D5h.LwdV0e[selected] .clOx1e:not(.l6PAOd){margin-left:8px}.d2D5h[selected] .k0Jjg:hover,.d2D5h.k0Jjg[selected]:hover{color:#1967d2}.d2D5h[selected] .k0Jjg:hover .kHtcsd,.d2D5h.k0Jjg[selected]:hover .kHtcsd{background-color:rgba(26,115,232,.08)}.brKmxb:focus-visible .d2D5h[selected],.d2D5h.k0Jjg[selected]:focus-visible,.d2D5h[selected] .k0Jjg:focus-visible{color:#1967d2}.p9pdc[selected]{color:var(--rrJJUc)}.p9pdc[selected] .niO4u{background-color:transparent}.p9pdc.rlt7Ub[selected] .d3o3Ad,.p9pdc.eFSWxd[selected] .d3o3Ad{display:none}.p9pdc[selected] .R04TOd{display:-webkit-box;display:-webkit-flex;display:flex}.p9pdc.LwdV0e[selected] .clOx1e:not(.l6PAOd){margin-left:8px}.p9pdc[selected] .k0Jjg:hover,.p9pdc.k0Jjg[selected]:hover .kHtcsd{background-color:rgba(26,115,232,0.08)}.fCrZyc[disabled]{color:#47474761}.fCrZyc.fCrZyc.fCrZyc.fCrZyc.fCrZyc.fCrZyc[disabled] .kHtcsd{background:transparent}.fCrZyc.fCrZyc.fCrZyc.fCrZyc.fCrZyc.fCrZyc[disabled] .niO4u{background:var(--YaIeMb);outline-color:#d2d2d261;cursor:auto;color:#47474761}@media (forced-colors:active){.fCrZyc[disabled] .niO4u{outline-color:GrayText;cursor:auto}.fCrZyc[disabled]{color:GrayText}}.RA6aK[selected]{color:var(--xPpiM)}.RA6aK[selected] .niO4u{background-color:var(--KIZPne)}.cqV32b[selected]{color:var(--xPpiM)}.cqV32b[selected] .niO4u{background-color:var(--KIZPne)}.iAyPwd[selected]{color:var(--xPpiM)}.iAyPwd[selected] .niO4u{background-color:var(--KIZPne)}.R04TOd{display:none}.A29zgf[selected] .clOx1e:not(.l6PAOd){margin-left:8px}.btku5b[selected] .k0Jjg:hover .kHtcsd,.btku5b.k0Jjg[selected]:hover .kHtcsd{background-color:#0b57d015}.rlt7Ub.erFMrf .clOx1e.clOx1e,.eFSWxd.erFMrf .clOx1e.clOx1e{margin-right:0}.WoA9Zd{margin:0 8px 0 4px}.sjVJQd{font-family:Arial,sans-serif;font-size:14px;font-weight:400;line-height:20px}.Tw6Cme{display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;-webkit-box-align:center;-webkit-align-items:center;align-items:center}.btku5b[selected] .XN0Yce{margin-right:8px}.btku5b.Tw6Cme[selected] .iY6rMb .kHtcsd,.btku5b.Tw6Cme[selected] .iY6rMb .niO4u{border-top-left-radius:0;border-bottom-left-radius:0}.btku5b.Tw6Cme[selected] .EDvPNc .kHtcsd,.btku5b.Tw6Cme[selected] .EDvPNc .niO4u{border-top-right-radius:0;border-bottom-right-radius:0}.btku5b.Tw6Cme[selected] .iY6rMb .niO4u .kHtcsd .clOx1e{margin-left:0}.btku5b:not([selected]) .EDvPNc{display:none}.btku5b.Tw6Cme[selected] .EDvPNc .niO4u{border-right:none}.btku5b.Tw6Cme[selected] .iY6rMb .niO4u{border-left:none}.S2mzKd.PrjL8c .niO4u{border-radius:99999px;height:40px;}.S2mzKd.A29zgf .k0Jjg,.S2mzKd.A29zgf .kHtcsd{border-radius:99999px}.zJUuqf{margin-bottom:4px}.AB4Wff{margin-left:16px}.wHYlTd{font-family:Arial,sans-serif;font-size:14px;line-height:22px}.yUTMj{font-family:Arial,sans-serif;font-weight:400}@-webkit-keyframes g-snackbar-show{from{pointer-events:none;-webkit-transform:translateY(0);transform:translateY(0)}to{-webkit-transform:translateY(-100%);transform:translateY(-100%)}}@keyframes g-snackbar-show{from{pointer-events:none;-webkit-transform:translateY(0);transform:translateY(0)}to{-webkit-transform:translateY(-100%);transform:translateY(-100%)}}@-webkit-keyframes g-snackbar-hide{from{-webkit-transform:translateY(-100%);transform:translateY(-100%)}to{-webkit-transform:translateY(0);transform:translateY(0)}}@keyframes g-snackbar-hide{from{-webkit-transform:translateY(-100%);transform:translateY(-100%)}to{-webkit-transform:translateY(0);transform:translateY(0)}}@-webkit-keyframes g-snackbar-show-content{from{opacity:0}}@keyframes g-snackbar-show-content{from{opacity:0}}@-webkit-keyframes g-snackbar-hide-content{to{opacity:0}}@keyframes g-snackbar-hide-content{to{opacity:0}}.LH3wG,.jhZvod{bottom:0;height:0;position:fixed;z-index:999}.Ox8Cyd{height:0;position:fixed;z-index:999}.E7Hdgb{box-sizing:border-box;visibility:hidden;display:inline-block}.yK6jqe,.Wu0v9b{box-sizing:border-box;visibility:hidden}.rTYTNb{-webkit-animation:g-snackbar-hide .4s cubic-bezier(0.4,0,0.2,1) both;animation:g-snackbar-hide .4s cubic-bezier(0.4,0,0.2,1) both;visibility:inherit}.UewPMd{-webkit-animation:g-snackbar-show .5s cubic-bezier(0.4,0,0.2,1) both;animation:g-snackbar-show .5s cubic-bezier(0.4,0,0.2,1) both;visibility:inherit}.b77HKf{background-color:#323232;padding:0 24px}.rIxsve{-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:box;display:-webkit-box;display:-webkit-flex;display:flex}.rTYTNb .rIxsve{-webkit-animation:g-snackbar-hide-content .35s cubic-bezier(0.4,0,0.2,1) both;animation:g-snackbar-hide-content .35s cubic-bezier(0.4,0,0.2,1) both}.UewPMd .rIxsve{-webkit-animation:g-snackbar-show-content .35s cubic-bezier(0.4,0,0.2,1) .15s both;animation:g-snackbar-show-content .35s cubic-bezier(0.4,0,0.2,1) .15s both}.Txngnb.Txngnb{line-height:20px}.Txngnb{color:#fff;-webkit-box-flex:1;-webkit-flex:1 1 auto;flex:1 1 auto;margin:14px 0;word-break:break-word}.sHFNYd{margin-right:-8px}@media (min-width:569px) and (min-height:569px){.LH3wG,.jhZvod{text-align:center}.Wu0v9b,.yK6jqe{display:inline-block;max-width:568px;min-width:288px;text-align:left}.b77HKf{border-radius:8px}.sHFNYd{margin-left:40px}}.V9O1Yd .rIxsve{display:block;padding:8px 0}.V9O1Yd .sHFNYd{margin-left:0}.V9O1Yd .sHFNYd g-flat-button{padding-left:0}.jhZvod{left:16px;right:auto}.LH3wG,.Ox8Cyd{left:0;right:0}.yK6jqe,.Wu0v9b,.E7Hdgb{position:relative}.G9jore{position:absolute;top:-24px;bottom:-24px;left:-24px;right:-24px}.zUdppc{padding-bottom:4px}.TkZZsf{padding-bottom:4px;padding-top:4px}.MdFDgb.HUQNIe{color:rgba(0,0,0,.26)}.czUY2e{background-color:var(--Pa8Wlb)}g-img{display:block}g-img{height:100%}.YQ4gaf{display:block;border:0}.u9wH7d .YQ4gaf{object-fit:fill}.mNsIhb .YQ4gaf{object-fit:cover}.tb08Pd .YQ4gaf{object-fit:contain}.wA1Bge{position:relative}.hhtjrc{-webkit-box-flex:0;-webkit-flex:none;flex:none}.ZGomKf{overflow:hidden}.LLO8yd{background-color:rgba(0,0,0,.03);position:absolute;top:0;bottom:0;pointer-events:none;left:0;right:0}.LqkKtf{-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:none;height:100%;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;left:0;opacity:.999;overflow:hidden;position:absolute;top:0;width:100%}.Iz740d.LqkKtf{border-radius:50%}.LqkKtf.DngrPc{left:50%;margin-left:-50vw;margin-right:-50vw;right:50%;width:100vw}.amp_re{position:relative}.QyJI3d{background-color:var(--xhUGwc);color:#666;box-shadow:0 4px 16px rgba(0,0,0,0.2)}.oQcPt{background-color:var(--xhUGwc)}.QyJI3d{border:1px solid rgba(0,0,0,.2);position:absolute;z-index:9120}.nFdFHf{-webkit-animation:g-bubble-show .2s forwards;animation:g-bubble-show .2s forwards}.bE3Kif{-webkit-animation:g-bubble-hide .2s forwards;animation:g-bubble-hide .2s forwards}@-webkit-keyframes g-bubble-show{from{opacity:0}to{opacity:1}}@keyframes g-bubble-show{from{opacity:0}to{opacity:1}}@-webkit-keyframes g-bubble-hide{from{opacity:1}to{opacity:0}}@keyframes g-bubble-hide{from{opacity:1}to{opacity:0}}.QyJI3d.QJnoze{border-radius:12px}.QyJI3d.SiOjJb{border-left-width:0;border-right-width:0;width:100%}.QyJI3d.PnQMie{background-color:#202124;border:1px solid rgba(0,0,0,0.5);color:#dadce0}.QyJI3d.LWen5c{background-color:#1a73e8;border:none;color:#fff;z-index:9100}.tYmfxe{-webkit-transform:translate(2.5px,1.8px) rotateZ(45deg);transform:translate(2.5px,1.8px) rotateZ(45deg);position:absolute;z-index:9121}[dir=rtl] .tYmfxe{-webkit-transform:translate(-2.5px,1.8px) rotateZ(45deg);transform:translate(-2.5px,1.8px) rotateZ(45deg)}.IBPZu.tYmfxe{-webkit-transform:translate(2.5px,-5.7px) rotateZ(45deg);transform:translate(2.5px,-5.7px) rotateZ(45deg)}[dir=rtl] .IBPZu.tYmfxe{-webkit-transform:translate(-2.5px,-5.7px) rotateZ(45deg);transform:translate(-2.5px,-5.7px) rotateZ(45deg)}.oQcPt{border-bottom:none;border-left:1px solid rgba(0,0,0,.2);border-right:none;border-top:1px solid rgba(0,0,0,.2);box-sizing:border-box;height:13.435px;width:13.435px}.IBPZu .oQcPt{border-bottom:1px solid rgba(0,0,0,.2);border-left:none;border-right:1px solid rgba(0,0,0,.2);border-top:none}.PnQMie .oQcPt{background-color:#202124;border-color:rgba(0,0,0,0.5)}.LWen5c .oQcPt{background-color:#1a73e8;border:none}.nnFGuf{display:none}.c5aZPb{cursor:pointer}.Dcltre{pointer-events:none}.TYQ8Af{clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;top:3px;right:3px}.JgzqYd{font-family:Arial,sans-serif;font-size:28px;line-height:36px}.Pqkn2e{font-family:Arial,sans-serif;font-size:16px;line-height:24px}.ZwRhJd{font-family:Arial,sans-serif;font-size:14px;line-height:18px}.MBeuO{font-family:Arial,sans-serif;font-size:20px;font-weight:400}.MBeuO{line-height:24px}.RES9jf{color:var(--YLNNHc)}.ZYHQ7e{color:var(--IXoxUe)}.GS5rRd{color:var(--JKqx2)}.GS5rRd:visited{color:#681da8}.iwY1Mb{height:0;opacity:0;display:block}.V8fWH{border:0;clip:rect(0 0 0 0);-webkit-clip-path:polygon(0 0,0 0,0 0);clip-path:polygon(0 0,0 0,0 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;width:1px;white-space:nowrap;-webkit-appearance:none;appearance:none;z-index:-1000;-webkit-user-select:none;user-select:none}.gW7zSc{display:block}.CqmPRe:active .aVlTpc span{-webkit-animation-timing-function:cubic-bezier(.2,.2,0,1);animation-timing-function:cubic-bezier(.2,.2,0,1);-webkit-animation-duration:.5s;animation-duration:.5s}@-webkit-keyframes shape-tween-right{50%{-webkit-transform:scaleY(.9) translateX(8%);transform:scaleY(.9) translateX(8%)}100%{-webkit-transform:none;transform:none}}@keyframes shape-tween-right{50%{-webkit-transform:scaleY(.9) translateX(8%);transform:scaleY(.9) translateX(8%)}100%{-webkit-transform:none;transform:none}}@-webkit-keyframes shape-tween-left{50%{-webkit-transform:scaleY(.9) translateX(-8%);transform:scaleY(.9) translateX(-8%)}100%{-webkit-transform:none;transform:none}}@keyframes shape-tween-left{50%{-webkit-transform:scaleY(.9) translateX(-8%);transform:scaleY(.9) translateX(-8%)}100%{-webkit-transform:none;transform:none}}.CqmPRe:active .KArJuc span{-webkit-animation-name:shape-tween-right;animation-name:shape-tween-right}.CqmPRe:active .YbCrzd span{-webkit-animation-name:shape-tween-left;animation-name:shape-tween-left}@-webkit-keyframes shape-tween-up{50%{-webkit-transform:scaleX(.9) translateY(-8%);transform:scaleX(.9) translateY(-8%)}100%{-webkit-transform:none;transform:none}}@keyframes shape-tween-up{50%{-webkit-transform:scaleX(.9) translateY(-8%);transform:scaleX(.9) translateY(-8%)}100%{-webkit-transform:none;transform:none}}.CqmPRe:active .oXqZxc span{-webkit-animation-name:shape-tween-up;animation-name:shape-tween-up}@-webkit-keyframes shape-tween-down{50%{-webkit-transform:scaleX(.9) translateY(8%);transform:scaleX(.9) translateY(8%)}100%{-webkit-transform:none;transform:none}}@keyframes shape-tween-down{50%{-webkit-transform:scaleX(.9) translateY(8%);transform:scaleX(.9) translateY(8%)}100%{-webkit-transform:none;transform:none}}.CqmPRe:active .TD5FQe span{-webkit-animation-name:shape-tween-down;animation-name:shape-tween-down}.Aajd3{padding-left:16px}.U09Jxd{padding-right:4px}.gxMdVd{padding-right:8px}.mWcf0e{cursor:pointer}@media (forced-colors:active){.CNbPnc{background-color:ButtonFace;border:1px solid transparent;border-color:ButtonBorder;color:ButtonText}}.VfL2Y{position:relative;}.YQpX9d{cursor:pointer;position:relative;}.LRZwuc{display:inline-block}.nKHyTc{color:var(--IXoxUe);float:right;font-size:12px;line-height:16px;padding-bottom:4px}.eDGqNd{color:var(--IXoxUe);float:right;font-size:12px;line-height:16px}.k62gjb:hover,.k62gjb .W7GCoc:hover{text-decoration:underline}.r2fjmd{margin-bottom:0px;margin-top:0px}g-dropdown-menu{display:inline-block;position:relative}.Jb0Zif g-dropdown-menu{vertical-align:middle}.WNN1b{background-color:var(--xhUGwc)}.W4XqN{cursor:pointer;background-color:var(--xhUGwc)}.GKXWV{border-top:1px solid #dadce0;height:0;margin-left:5px;margin-right:5px}.eNRwyf{height:100%;width:100%}.adGN6[disabled]{pointer-events:none;cursor:default;background-color:var(--YaIeMb)}.pkWBse{box-shadow:0 2px 10px 0 rgba(0,0,0,0.2)}.pkWBse{border-radius:8px}.UjBGL{display:block}.CcNe6e{cursor:pointer;display:inline-block}.iRQHZe{position:absolute}.Qaqu5{position:relative}.shnMoc.CcNe6e{display:block}.v4Zpbe.CcNe6e{display:-webkit-box;display:-webkit-flex;display:flex;height:100%;width:100%}.PBn44e{border-radius:8px}.yKUyj .EpPYLd:first-of-type{border-top-left-radius:8px;border-top-right-radius:8px}.yKUyj .EpPYLd:last-of-type{border-bottom-left-radius:8px;border-bottom-right-radius:8px}.yTik0{border:none;display:block;outline:none}.wplJBd{white-space:nowrap}.JM22S::-webkit-scrollbar{width:8px}.JM22S::-webkit-scrollbar-thumb{background-color:#bababa;border-right:4px solid #fff}.iQXTJe{padding:5px 0}.Zt0a5e.LGiluc{border-top-color:var(--gS5jXb)}.Zt0a5e.LGiluc,.Zt0a5e.EpPYLd[disabled]{color:rgba(0,0,0,0.26)!important}.CjiZvb,.GZnQqe.EpPYLd:active{background-color:rgba(0,0,0,.1)}.EpPYLd{display:block;position:relative}.YpcDnf{padding:0 16px;vertical-align:middle}.YpcDnf.HG1dvd{padding:0}.HG1dvd>*{padding:0 16px}.WtV5nd .YpcDnf{padding-left:28px}.Zt0a5e .YpcDnf{line-height:48px}.GZnQqe .YpcDnf{line-height:23px}.EpPYLd:hover{cursor:pointer}.EpPYLd,.CB8nDe:hover{cursor:default}.LGiluc,.EpPYLd[disabled]{pointer-events:none;cursor:default}@media (forced-colors:active){.EpPYLd[disabled]{color:GrayText}}.LGiluc{border-top:1px solid;height:0;margin:5px 0}.Zt0a5e.CB8nDe{background:no-repeat left 8px center}.Zt0a5e.CB8nDe{background-image:url(https://ssl.gstatic.com/images/icons/material/system/1x/done_black_16dp.png)}@media (forced-colors:active){.Zt0a5e.CB8nDe{background-image:url(https://ssl.gstatic.com/images/icons/material/system/1x/done_white_16dp.png)}}.GZnQqe.CB8nDe{background:no-repeat left center}.GZnQqe.CB8nDe{background-image:url(https://ssl.gstatic.com/ui/v1/menu/checkmark2.png)}@media (forced-colors:active){.GZnQqe.CB8nDe{background-image:url(https://ssl.gstatic.com/ui/v1/menu/checkmark2-light.png)}}.GZnQqe.LGiluc,.GZnQqe.EpPYLd[disabled]{opacity:61%}.GZnQqe.LGiluc{border-top-color:var(--gS5jXb)}.eCcUA,.cDnxO{pointer-events:none;position:absolute;top:0;left:0;width:100%;height:100%;border-radius:50%}.rLdWfe{position:absolute;border-radius:inherit;top:0;left:0;width:100%;height:100%}.MDfoTd,.hdqIFe{pointer-events:none;position:absolute;top:0;left:0;width:100%;height:100%}.MDfoTd,.cDnxO{opacity:0}.hdqIFe,.cDnxO{overflow:hidden}.bKvogb .MDfoTd,.bKvogb .hdqIFe{border-radius:50%}.bKvogb .eCcUA{overflow:hidden}.LwVyHd{-webkit-transition:max-height .3s;transition:max-height .3s;overflow:hidden}.Yh3tf{pointer-events:none;position:absolute!important;right:0;color:#5e5e5e;top:50%;margin-top:-12px;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-align:center;-webkit-align-items:center;align-items:center}.FXMOpb .Yh3tf{margin-top:-14px}.FXMOpb .MLgx0e{-webkit-transform:rotateX(180deg);transform:rotateX(180deg)}.ydSoC{padding-left:8px}.kGfs{position:relative}.Yh3tf.chvYFc{background:var(--XKMDxc);border-radius:25px;margin-top:-18px;padding:6px}.SpKsUc{margin:0 -10px;padding:0 10px}.V1sL5c{overflow:visible}.S8PBwe{max-height:0;display:none}.hObAcc{margin-left:4px;margin-right:4px}.gTewb{padding-left:8px;padding-right:8px}.thsZXc{background:#1a73e8}.hiQRQc{background:#e8eaed}.Bb1JKe{padding-bottom:8px}.ouy7Mc{padding-left:16px;padding-right:16px}.M8CEed{padding-top:12px}.z1asCe{display:inline-block;fill:currentColor;height:24px;line-height:24px;position:relative;width:24px}.z1asCe svg{display:block;height:100%;width:100%}
	</style>
	<script async="" type="text/javascript" charset="UTF-8" src="./いんでっくす_files/rs=AA2YrTv0taM5qVgw38gU_15kX9WFXe5TPw"
	nonce=""></script>
	<link type="text/css" href="./いんでっくす_files/rs=AA2YrTsXU5hjdOZrxXehYcpWx5cYm18ejw"
	rel="stylesheet">
	<style data-late-css="">
	c-wiz{contain:style}c-wiz>c-data{display:none}c-wiz.rETSD{contain:none}c-wiz.Ubi8Z{contain:layout style}.jbBItf{display:block;position:relative}.DU0NJ{bottom:0;left:0;position:absolute;right:0;top:0}.lP3Jof{display:inline-block;position:relative}.nNMuOd{-webkit-animation:qli-container-rotate 1568.2352941176ms linear infinite;animation:qli-container-rotate 1568.2352941176ms linear infinite}@-webkit-keyframes qli-container-rotate{from{-webkit-transform:rotate(0);transform:rotate(0)}to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}}@keyframes qli-container-rotate{from{-webkit-transform:rotate(0);transform:rotate(0)}to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}}.RoKmhb{height:100%;opacity:0;position:absolute;width:100%}.nNMuOd .VQdeab{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-blue-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-blue-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.nNMuOd .IEqiAf{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-red-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-red-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.nNMuOd .smocse{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-yellow-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-yellow-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.nNMuOd .FlKbCe{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-green-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both,qli-green-fade-in-out 5332ms cubic-bezier(0.4,0,0.2,1) infinite both}.BSnLb .nNMuOd .RoKmhb{-webkit-animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-fill-unfill-rotate 5332ms cubic-bezier(0.4,0,0.2,1) infinite both;opacity:0.99}@-webkit-keyframes qli-fill-unfill-rotate{0%{-webkit-transform:rotate(0);transform:rotate(0)}12.5%{-webkit-transform:rotate(135deg);transform:rotate(135deg)}25%{-webkit-transform:rotate(270deg);transform:rotate(270deg)}37.5%{-webkit-transform:rotate(405deg);transform:rotate(405deg)}50%{-webkit-transform:rotate(540deg);transform:rotate(540deg)}62.5%{-webkit-transform:rotate(675deg);transform:rotate(675deg)}75%{-webkit-transform:rotate(810deg);transform:rotate(810deg)}87.5%{-webkit-transform:rotate(945deg);transform:rotate(945deg)}100%{-webkit-transform:rotate(3turn);transform:rotate(3turn)}}@keyframes qli-fill-unfill-rotate{0%{-webkit-transform:rotate(0);transform:rotate(0)}12.5%{-webkit-transform:rotate(135deg);transform:rotate(135deg)}25%{-webkit-transform:rotate(270deg);transform:rotate(270deg)}37.5%{-webkit-transform:rotate(405deg);transform:rotate(405deg)}50%{-webkit-transform:rotate(540deg);transform:rotate(540deg)}62.5%{-webkit-transform:rotate(675deg);transform:rotate(675deg)}75%{-webkit-transform:rotate(810deg);transform:rotate(810deg)}87.5%{-webkit-transform:rotate(945deg);transform:rotate(945deg)}100%{-webkit-transform:rotate(3turn);transform:rotate(3turn)}}@-webkit-keyframes qli-blue-fade-in-out{0%{opacity:0.99}25%{opacity:0.99}26%{opacity:0}89%{opacity:0}90%{opacity:0.99}100%{opacity:0.99}}@keyframes qli-blue-fade-in-out{0%{opacity:0.99}25%{opacity:0.99}26%{opacity:0}89%{opacity:0}90%{opacity:0.99}100%{opacity:0.99}}@-webkit-keyframes qli-red-fade-in-out{0%{opacity:0}15%{opacity:0}25%{opacity:0.99}50%{opacity:0.99}51%{opacity:0}}@keyframes qli-red-fade-in-out{0%{opacity:0}15%{opacity:0}25%{opacity:0.99}50%{opacity:0.99}51%{opacity:0}}@-webkit-keyframes qli-yellow-fade-in-out{0%{opacity:0}40%{opacity:0}50%{opacity:0.99}75%{opacity:0.99}76%{opacity:0}}@keyframes qli-yellow-fade-in-out{0%{opacity:0}40%{opacity:0}50%{opacity:0.99}75%{opacity:0.99}76%{opacity:0}}@-webkit-keyframes qli-green-fade-in-out{0%{opacity:0}65%{opacity:0}75%{opacity:0.99}90%{opacity:0.99}100%{opacity:0}}@keyframes qli-green-fade-in-out{0%{opacity:0}65%{opacity:0}75%{opacity:0.99}90%{opacity:0.99}100%{opacity:0}}.beDQP{display:inline-block;height:100%;overflow:hidden;position:relative;width:50%}.FcXfi{box-sizing:border-box;height:100%;left:45%;overflow:hidden;position:absolute;top:0;width:10%}.SPKFmc{border-radius:50%;border:3px solid transparent;box-sizing:border-box}@media (forced-colors:active),(prefers-contrast:more){.beDQP:last-child .SPKFmc{border:none}}.x3SdXd{width:200%}.J7uuUe{-webkit-transform:rotate(129deg);transform:rotate(129deg)}.sDPIC{left:-100%;-webkit-transform:rotate(-129deg);transform:rotate(-129deg)}.tS3P5{left:-450%;width:1000%}.VQdeab .SPKFmc{border-color:#4285f4}.IEqiAf .SPKFmc{border-color:#ea4335}.smocse .SPKFmc{border-color:#fbbc04}.FlKbCe .SPKFmc{border-color:#34a853}.RoKmhb .J7uuUe{border-bottom-color:transparent;border-right-color:transparent}.RoKmhb .sDPIC{border-bottom-color:transparent;border-left-color:transparent}.RoKmhb .tS3P5{border-bottom-color:transparent}.GgTJWe .nNMuOd .J7uuUe{-webkit-animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both}.GgTJWe .nNMuOd .sDPIC{-webkit-animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both}.BSnLb .nNMuOd .J7uuUe{-webkit-animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-left-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;border-left-color:var(--EpFNW);border-top-color:var(--EpFNW)}.BSnLb .nNMuOd .sDPIC{-webkit-animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;animation:qli-right-spin 1333ms cubic-bezier(0.4,0,0.2,1) infinite both;border-right-color:var(--EpFNW);border-top-color:var(--EpFNW)}.BSnLb .nNMuOd .tS3P5{border-color:var(--EpFNW);border-bottom-color:transparent}@-webkit-keyframes qli-left-spin{0%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}50%{-webkit-transform:rotate(-5deg);transform:rotate(-5deg)}100%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}}@keyframes qli-left-spin{0%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}50%{-webkit-transform:rotate(-5deg);transform:rotate(-5deg)}100%{-webkit-transform:rotate(130deg);transform:rotate(130deg)}}@-webkit-keyframes qli-right-spin{0%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}50%{-webkit-transform:rotate(5deg);transform:rotate(5deg)}100%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}}@keyframes qli-right-spin{0%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}50%{-webkit-transform:rotate(5deg);transform:rotate(5deg)}100%{-webkit-transform:rotate(-130deg);transform:rotate(-130deg)}}.ea0Lbe{background:#fff;border-radius:24px;box-shadow:0px 4px 6px rgba(32,33,36,0.28);margin-left:-4px;margin-top:0;position:absolute;top:-4px;width:calc(100% + 8px);z-index:989}.KoWHpd{margin:20px}.BiKNf{-webkit-align-self:flex-end;align-self:flex-end;cursor:pointer;display:-webkit-box;display:-webkit-flex;display:flex;padding:14px;position:absolute;right:6px;top:6px}.p4pvTd{color:rgb(32,33,36);font-family:"Google Sans Display",Roboto,Arial,sans-serif;font-size:16px;line-height:28px;margin-bottom:14px;text-align:center;letter-spacing:.1px}.BH9rn{-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;-webkit-box-orient:horizontal;-webkit-box-direction:normal;-webkit-flex-direction:row;flex-direction:row;-webkit-box-flex:1;-webkit-flex-grow:1;flex-grow:1;-webkit-box-pack:initial;-webkit-justify-content:initial;justify-content:normal;padding-top:16px}.gIYJUc{background:rgb(248,249,250);border:1px dashed #c0c0c0;border-radius:8px;box-sizing:border-box;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-orient:vertical;-webkit-box-direction:normal;-webkit-flex-direction:column;flex-direction:column;-webkit-box-flex:1;-webkit-flex-grow:1;flex-grow:1;height:280px;position:relative;width:100%}.Ndj4R{border:1px dashed #c0c0c0}.id5vMb{border:1px dashed #c0c0c0}.f6GA0{height:100%;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;margin-top:0}.f6GA0,.CacfB{-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-orient:vertical;-webkit-box-direction:normal;-webkit-flex-direction:column;flex-direction:column}.f6GA0,.CacfB,.Ua7Yuf{border-radius:8px;-webkit-box-flex:1;-webkit-flex-grow:1;flex-grow:1}.CacfB{background:#f0f6ff;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;height:100%;width:100%}.ZeVBtc{color:rgb(95,99,104);font-family:"Google Sans",Roboto,Arial,sans-serif;font-size:16px;line-height:25px;max-width:300px}.alTBQe{-webkit-box-align:center;-webkit-align-items:center;align-items:center;background-color:rgb(252,232,230);border-top-left-radius:8px;border-top-right-radius:8px;-webkit-box-pack:justify;-webkit-justify-content:space-between;justify-content:space-between;left:0;position:absolute;right:0;top:0}.OHzWjb{color:rgb(179,20,18);-webkit-box-flex:1;-webkit-flex:1;flex:1;font-family:"Google Sans",Roboto,Arial,sans-serif;font-size:12px;padding:5px;text-align:center}.Ua7Yuf{-webkit-box-align:center;-webkit-align-items:center;align-items:center;-webkit-align-self:center;align-self:center;background:#f0f6ff;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-flex:1;-webkit-flex:1;flex:1;-webkit-box-orient:vertical;-webkit-box-direction:normal;-webkit-flex-direction:column;flex-direction:column;height:100%;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;width:100%}.wHH8af{color:rgb(95,99,104);font-family:"Google Sans",Roboto,Arial,sans-serif;font-size:16px;line-height:25px;margin-top:12px}.DV7the{color:rgb(25,103,210);cursor:pointer;white-space:nowrap}.DV7the.RiECff:focus{outline:none}.DV7the:hover,.DV7the:hover{text-decoration:underline}.DV7the:focus{text-decoration:underline}.ArIAXb{fill:rgb(241,243,244)}.qOFLsb{fill:rgb(218,220,224)}.Aye1k{width:inherit;position:relative;display:block}.RaoUUe{display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;margin-right:18px}.e8Eule{box-sizing:border-box;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-orient:vertical;-webkit-box-direction:normal;-webkit-flex-direction:column;flex-direction:column;padding:0 20px 20px;width:100%}.YJx25{-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex}.diOlIe{border-top:1px solid rgb(232,234,237);-webkit-box-flex:1;-webkit-flex-grow:1;flex-grow:1;height:0}.aHK1bd{color:rgb(95,99,104);cursor:default;-webkit-flex-shrink:0;flex-shrink:0;font-family:"Google Sans Display",Roboto,Arial,sans-serif;font-size:14px;margin-left:20px;margin-right:20px}.PXT6cd{display:-webkit-box;display:-webkit-flex;display:flex;margin-top:14px}.cB9M7{background-color:#fff;border:1px solid rgb(218,220,224);color:rgb(60,64,67);border-radius:36px;display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;-webkit-box-flex:1;-webkit-flex-grow:1;flex-grow:1;font-size:14px;font-family:"Google Sans Display",Roboto,Arial,sans-serif;height:40px;padding:0 24px;width:100%;outline:none}.lensUploadWizwebUploadDialogUrlInputInputBox ::-webkit-input-placeholder{color:rgb(128,134,139)}.cB9M7 ::placeholder{color:rgb(128,134,139)}.cB9M7:hover{border:1px solid rgb(60,64,67)}.cB9M7:focus{border:1px solid rgb(25,103,210)}.cB9M7:active{border:1px solid rgb(25,103,210)}.Qwbd3{-webkit-box-align:center;-webkit-align-items:center;align-items:center;background:#fff;border-radius:32px;border:1px solid rgb(218,220,224);color:rgb(26,115,232);cursor:pointer;display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;-webkit-flex-shrink:0;flex-shrink:0;font-family:"Google Sans",Roboto,Arial,sans-serif;font-size:14px;-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center;letter-spacing:.25px;margin-left:8px;outline:0;padding:8px 24px}.Qwbd3:hover{background:rgba(25,103,210,0.08);color:rgb(26,115,232);border:1px solid rgb(218,220,224)}.Qwbd3:focus{background:rgba(25,103,210,0.08);border:1px solid rgb(25,103,210);color:rgb(26,115,232)}.Qwbd3:active{background:rgba(25,103,210,0.14);border:1px solid rgb(218,220,224);color:rgb(26,115,232)}sentinel{}
	</style>
	<style data-late-css="">
	.MTIaKb,.LwDUdc,.FAoEle,.RlTCPd,.wPNfjb,.caNvfd,.Vnob4b,.bbxTBb,.DpgmK,.YKUhfb,.uNnvb,.aVsZpf,.RoOVmf,.dIfvQd,.V3Ezn,.Enb9pe,.mYuoaf,.kJSB8,.tUr4Kc,.iQMtqe{--Yi4Nb:var(--mXZkqc);--pEa0Bc:var(--bbQxAb);--kloG3:var(--mXZkqc);--YaIeMb:var(--XKMDxc);--Pa8Wlb:var(--Nsm0ce);--izGsqb:var(--Nsm0ce);--todMNcl:var(--EpFNW);--p9J9c:var(--Nsm0ce)}:root{--KIZPne:#a3c9ff;--xPpiM:#001d35;--Ehh4mf:var(--Nsm0ce)}:root{--Yi4Nb:#d2d2d2;--pEa0Bc:#474747;--kloG3:#d2d2d2;--YaIeMb:#f7f8f9;--Pa8Wlb:#0b57d0;--izGsqb:#0b57d0;--todMNcl:#fff;--p9J9c:#0b57d0}.EpPYLd{display:block;position:relative}.YpcDnf{padding:0 16px;vertical-align:middle}.YpcDnf.HG1dvd{padding:0}.HG1dvd>*{padding:0 16px}.WtV5nd .YpcDnf{padding-left:28px}.Zt0a5e .YpcDnf{line-height:48px}.GZnQqe .YpcDnf{line-height:23px}.EpPYLd:hover{cursor:pointer}.EpPYLd,.CB8nDe:hover{cursor:default}.LGiluc,.EpPYLd[disabled]{pointer-events:none;cursor:default}@media (forced-colors:active){.EpPYLd[disabled]{color:GrayText}}.LGiluc{border-top:1px solid;height:0;margin:5px 0}.Zt0a5e.CB8nDe{background:no-repeat left 8px center}.Zt0a5e.CB8nDe{background-image:url(https://ssl.gstatic.com/images/icons/material/system/1x/done_black_16dp.png)}@media (forced-colors:active){.Zt0a5e.CB8nDe{background-image:url(https://ssl.gstatic.com/images/icons/material/system/1x/done_white_16dp.png)}}.GZnQqe.CB8nDe{background:no-repeat left center}.GZnQqe.CB8nDe{background-image:url(https://ssl.gstatic.com/ui/v1/menu/checkmark2.png)}@media (forced-colors:active){.GZnQqe.CB8nDe{background-image:url(https://ssl.gstatic.com/ui/v1/menu/checkmark2-light.png)}}.GZnQqe.LGiluc,.GZnQqe.EpPYLd[disabled]{opacity:61%}.GZnQqe.LGiluc{border-top-color:var(--gS5jXb)}sentinel{}
	</style>
</head>

<body jsmodel="hspDDf " jsaction="xjhTIf:.CLIENT;O2vyse:.CLIENT;IVKTfe:.CLIENT;Ez7VMc:.CLIENT;R6Slyc:.CLIENT;hWT9Jb:.CLIENT;WCulWe:.CLIENT;VM8bg:.CLIENT;qqf0n:.CLIENT;A8708b:.CLIENT;YcfJ:.CLIENT;szjOR:.CLIENT;JL9QDc:.CLIENT;kWlxhc:.CLIENT;qGMTIf:.CLIENT;ydZCDf:.CLIENT">
	<style>
	.L3eUgb{display:flex;flex-direction:column;height:100%}.o3j99{flex-shrink:0;box-sizing:border-box}.n1xJcf{height:60px}.LLD4me{min-height:150px;height:calc(100% - 560px);max-height:290px}.yr19Zb{min-height:92px}.ikrT4e{max-height:160px}.mwht9d{display:none}.ADHj4e{padding-top:0px;padding-bottom:85px}.oWyZre{width:100%;height:500px;border-width:0}.qarstb{flex-grow:1}
	</style>
	<div class="L3eUgb" data-hveid="1">
		<div class="o3j99 n1xJcf Ne6nSd" role="navigation">
			<style>
			.Ne6nSd{display:flex;align-items:center;padding:6px}.LX3sZb{display:inline-block;flex-grow:1}
			</style>
			<div class="LX3sZb">
				<div>
					<div class="gb_ha gb_dd gb_9a gb_Cd gb_Ca gb_Sc" id="gb">
						<div class="gb_ud gb_7a gb_id" data-ogsr-up="">
							<div>
								<div class="gb_o gb_A gb_Pf gb_Ff" data-ogbl="">
									<div class="gb_z gb_A"><a class="gb_y" aria-label="Gmail " data-pid="23" href="https://mail.google.com/mail/&amp;ogbl"
										target="_top">Gmail</a></div>
									<div class="gb_z gb_A"><a class="gb_y" aria-label="画像を検索する " data-pid="2" href="https://www.google.co.jp/imghp?hl=ja&amp;ogbl"
										target="_top">画像</a></div>
								</div>
							</div>
							<div class="gb_Ld">
								<div class="gb_Zc">
									<div class="gb_k gb_Fd gb_A" data-ogsr-fb="true" data-ogsr-alt="" id="gbwa">
										<div class="gb_f">
											<a class="gb_d" aria-label="Google アプリ" href="https://www.google.co.jp/intl/ja/about/products"
											aria-expanded="false" role="button" tabindex="0">
												<svg class="gb_h" focusable="false" viewBox="0 0 24 24">
													<path d="M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z"></path>
													<image src="https://ssl.gstatic.com/gb/images/bar/al-icon.png"
													alt="" height="24" width="24" style="border:none;display:none \9"></image>
												</svg>
											</a>
										</div>
									</div>
								</div><a class="gb_va gb_nd gb_ed gb_9d" aria-label="ログイン" href="https://accounts.google.com/ServiceLogin?hl=ja&amp;passive=true&amp;continue=https://www.google.co.jp/&amp;ec=GAZAmgQ"
								target="_top"><span class="gb_Bd">ログイン</span></a></div>
							<div aria-hidden="true"
							style="overflow: hidden; position: absolute; top: 0px; visibility: hidden; width: 370px; z-index: 991; height: 0px; margin-top: 49px; transition: height 0.3s ease-in-out; right: 0px; margin-right: 4px;">
								<iframe role="presentation" frameborder="0" scrolling="no" name="app" src="./いんでっくす_files/so.html"
								style="height: 100%; width: 100%; color-scheme: light; visibility: hidden;"></iframe>
							</div>
							<div style="overflow: hidden; position: absolute; top: 0px; visibility: hidden; width: 420px; z-index: 991; height: 280px; margin-top: 70px; right: 0px; margin-right: 25px;"></div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="o3j99 LLD4me yr19Zb LS8OJ">
			<style>
			.LS8OJ{display:flex;flex-direction:column;align-items:center}.k1zIA{height:100%;margin-top:auto}
			</style>
			<div class="k1zIA rSk4se">
				<style>
				.rSk4se{max-height:92px;position:relative}.lnXdpd{max-height:100%;max-width:100%;object-fit:contain;object-position:center bottom;width:auto}
				</style><img class="lnXdpd" alt="Google" height="92" src="./いんでっくす_files/googlelogo_color_272x92dp.png"
				srcset="/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png 1x, /images/branding/googlelogo/2x/googlelogo_color_272x92dp.png 2x"
				width="272" data-csiid="KnDAZtO4CObk2roP-pvLiAs_1" data-atf="1"></div>
		</div>
		<div class="o3j99 ikrT4e om7nvf">
			<style>
			.om7nvf{padding:20px}
			</style>
			<dialog class="spch-dlg" id="spch-dlg">
				<div class="spch" style="display:none" id="spch">
					<style>
					.spch-dlg{background:transparent;border:none}.spch{background:var(--xhUGwc);height:100%;left:0;opacity:0;overflow:hidden;position:fixed;text-align:left;top:0;visibility:hidden;width:100%;z-index:10000;transition:visibility 0s linear 0.218s,background-color 0.218s;}.s2fp.spch{opacity:1;transition-delay:0s;visibility:visible;}.pz5bj{background:none;border:none;color:var(--IXoxUe);cursor:pointer;font-size:26px;right:0;line-height:15px;opacity:.6;margin:-1px -1px 0 0;padding:0 0 2px 0;height:48px;width:48px;position:absolute;top:0;z-index:10}.pz5bj:hover{opacity:.8}.pz5bj:active{opacity:1}.spchc{display:block;height:42px;pointer-events:none;margin:auto;position:relative;top:0;margin-top:312px;max-width:572px;min-width:534px;padding:0 223px}.inner-container{height:100%;opacity:.1;pointer-events:none;width:100%;transition:opacity .318s ease-in;}.s2ml .inner-container,.s2ra .inner-container,.s2er .inner-container,.OJaju .inner-container{opacity:1;transition:opacity 0s}
					</style>
					<style>
					.google-logo{background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALwAAABACAQAAAAKENVCAAAI/ElEQVR4Ae3ae3BU5RnH8e/ZTbIhhIRbRIJyCZcEk4ZyE4RBAiRBxRahEZBLQYUZAjIgoLUWB6wjKIK2MtAqOLVUKSqWQW0ZaOQq0IFAIZVrgFQhXAOShITEbHY7407mnPfc8u6ya2f0fN6/9rzvc87Z39nbed/l/8OhIKMDQ+hHKp1JJB6FKq5QQhH72MZ1IsDRhvkU4bds9WxlLNE4wqg9q6jBL9G+4knc/HB9qXmuG4goD89TjT+IVkimE/zt6sYh/EG3WmaiOMGHbgQ38YfY3ibKCV6GMabHWY0bo+Ps5jjnuYlCczrSk8Hcgd5U1rONoDnG48Ova2W8RGeMXAxiHfWakT4mOx81oRiG1/C5vYh47KSx5fZid4JvxxVd7MdIp3EK06kNNXYneIWtutgLaIasQUwkJE7wE3SxbycWR8SD93BOiL2YRBwRDN5FwOPchaqecZQTQQ4XAApz0FrFQSLPwQD8mlZNEt8L5841D62/cJVIi2cgPelEAlBOCYfYSxXymjKAXqSQAFRwloPspRp5dzOMHiTThEqK2c1OvGHIsg/30YUWKHzDKfZwEB+2xBn3gUSSwmA+MpluruYDySMPYD23TOrX0V/q+CPZYai+yHw8wKscbmhMD+IVfyevcMlkuvxXxGOphTD4Gi4iJ40C/DZtM12wk8Lfbes/oSN27mGPZW0RnVmvebxIMng3z1Bluddz5Mh9wm8icqZIzPHfZDxW8qhotL6cUVh5zP74XOBg0MEnsgW/bfMxzyIOYdgSIuV5/JJtPmZmSlb7mI6ZGTLVQQafSKHUvp7BxFxhSD6N8UsH4An5aT+J3mNB1T+K3hj8YQ/ezRbpvY3CYKEwYFLYgvfTkQZ9qTN8nS3lIdJJZwTLDdNztfwUrTTDp+hllmnqrxo+sLqi1dWwuFPKYnK5h0we5c/UhhT8fF1FHWsZTis8dGAyB4S+67RF5wVhwC/DGHxvAqI4Imyv50Vi0YpjsW4l4AAuGii63yE+lhCHVlOW6o79TxRN/ee64y/SHb8TO4MOvq3uYh6iO1oufiP0r0VnjtA9K4zBDzSdgKtjJGbyqBfG5dFguC62sZiZoLt0Qy3qvYzCKIZNQQYvXupdxGO0Rni5dLebl1wexuD7A4DuC+gprMwTxu2hwT+E7c9iZYEw7lMaiBPeczAXT3EQwcdwTbP1Eq3RiyaPvcIe/4igj9C5NYzBpwOQKmzbh4IVF4dMviOShHfCEdxYieKY8M5qCUCy8E4oxIWVnwcRfK4wdhqitiyk1JBHJc3UU4UT+HDRYADR1GEnB2s9WYrqssn41/BjxcdrrEOVzRogS4hqOfVY8fI6qzWXYTAbgRwUVMvwYeUzzpKCnMGobvIeDRTuZyajiMLoMG2oRONfwnV5kNDNFH5ZKAD8SbPtFrHYaSr8+nkLgCXC53sCdloJz+RlAFYJv5bisPOG9Cv+U+F+O6AZM4Sx2iz+QKZxWrgArSmEbiAIpwvQGdV/qMFOFUdRdTbUn6QCO9c4bajvJhy/GjuFyOqEqhhIZyUXWEk6esd4imTyKTIG/1e08kghNNEMR7WfgERUpTTmPKrmIdSXGupbiHu3dQFZCagy2MGXzCAekZcPySKDlVSYTwsf5QB9aeBiCWMJxcO0RPU5AW5UPuyJI9xhr/diz4ssF6ohGJXyFmu42Fj5MrTGMILgKTyHqpoCAipR3YE9cURFWOorUCVhrzWyKrFWwGg68hIXG79uGziG1rt0IFhPcC+qj6gioARVJm7sRPMTVCWG+u54sBNHqm19Ji7sZCDrv5gp53ekkcNGvHJvGB+zdVd+M60JRi/eREt9VIQqgfuxM5Q4VEcM9R5ysfMAUaA78iFUzRmIfb2sw+j9m6m042lOEqS1hv+R3Y2svpSJCxJCn9hjR5ztywSgg7BtGwpWFHYLY+8CIB2/5Jppj5BvoE7Qz/a8bCVSrIv+quQrYCLVQl0NXVEpnBF6f4aVX+guvELAPmH7GMk/ZX1BgKJb2szBnEJBEMFHUyY841SsjGcr7bGVabLC8z6dsJPC3ww1sxE9LfTeoAdmeumOPkNzYcUb776Y6aebOh5Hg6m6l1MaZhYGOUn2sjD6MAmYyeIWfiqYhoKNLJNlaC/ryCUGvRhyWUedYfx7KIiack4XfZ5ujMI4XewlxIpzMEL04w31k3STtEW4NWd6Uugr4yFEHt4Ielo4iRvC+P20R6QwTZPnFtpjI4dKi5veAlbwLPnM4NesZDs3Tcd9RgxGIw3jdjCeO1FQSGYiuw39D6A1CJ+u/wsm0pZA/STDEnY9A9DKMtRvZjStAIVOzOJMSAsh+YaMltGXGEChHVPYr+s/igsbPTmHP8T2IR7MvW46voZa0+2voLfAor7GdPtz6C0yHVfNt4S+9KewwXTJ8xtumWyv5T6w14pNIYTu40VcWHHzvvSe3sWFnsIq6foVKCb1qyOw2N2EnZJ7+5aRSFAYS2lQp3maLOy5WS61pyW4MKOwCJ/E5X8BBTMuXsW+tpITQQYPcXws8Zyuk420eOZyQSqqy8zDg4yH+cp2T2cYjp1sim3rTzEEO4/YPKNL9AvpD00K+ZTbnZXwc1KSh9FspNrmDbSZicQirwmzLMI7Qb7EnjxM57hp/TGmEUNjEljAZUNtHW/TGvhA+J6QCx4gicVcNT2r7TyIgoEiGf+99CeVLiTSDKimjK85QSH7qCJ4Cr0YRi9SaI6fG5zlIAUcwS9d34Nsen9Xz3f1hRRQJF0fzVCyyaQdcZRzil18zCUAPtHc3s3mTYIRzWCGkEEH4vFSxmn2s5kSJDgOGP/l4Ii8aOHetzeOsIhiNAX0wVq28O3lwXHbklnIeQJ/PHJhQbh72YXjts3Eq4n0t5h7BL+mzcVx29Kpxy9E70IvV5h7qiEJRxiswC+0feTgJkAhg3d098S/J8IUfhziOUAaouscoYJmpNIO0WXSuYYjLLpxFb9U85KNI4wyKJWKfQKOMEtmm33sXCCbCHC4mMxZIWpx/aglEeNwM4J3KNb8jvmaDTxBIt8jhR8vD22IpYYr1PBD5HA4HP8DxVcxdwELEFUAAAAASUVORK5CYII=) no-repeat center;background-size:94px 32px;height:32px;width:94px;top:8px;opacity:0;float:right;left:255px;pointer-events:none;position:relative;transition:opacity .5s ease-in,left .5s ease-in}
					</style>
					<button class="pz5bj" id="spchx" aria-label="閉じる"><span style="height:16px;line-height:16px;width:16px" class="z1asCe wuXmqc"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"></path></svg></span></button>
					<div
					class="spchc" id="spchc">
						<div class="inner-container">
							<div class="button-container">
								<style>
								.LgbsSe{background-color:#fff;border:1px solid #f8f9fa;border-radius:100%;bottom:0;box-shadow:0 2px 5px rgba(0,0,0,.1);cursor:pointer;display:inline-block;opacity:0;pointer-events:none;position:absolute;right:0;transition:background-color 0.218s,border 0.218s,box-shadow 0.218s;transition-delay:0;position:absolute;opacity:0;left:0;top:0}.s2fp .LgbsSe{opacity:1;pointer-events:auto;transform:scale(1);}.s2ra .LgbsSe{background-color:#ea4335;border:0;box-shadow:none}.r8s4j{background-color:#dadce0;border-radius:100%;display:inline-block;opacity:1;pointer-events:none;position:absolute;transform:scale(.01);transition:opacity 0.218s;height:301px;left:-69px;top:-69px;width:301px;}.button-container{pointer-events:none;position:relative;transition:transform 0.218s,opacity 0.218s ease-in;transform:scale(.1);height:165px;width:165px;right:-70px;top:-70px;float:right;}.s2fp .button-container{transform:scale(1)}.s2ra .LgbsSe:active{background-color:#c5221f}.LgbsSe:active{background-color:#f8f9fa}
								</style><span class="r8s4j" id="spchl"></span><span class="LgbsSe" id="spchb"><div class="microphone"><style>.microphone{height:87px;pointer-events:none;position:absolute;width:42px;top:47px;transform:scale(1);left:43px;}.receiver{background-color:#999;border-radius:30px;height:46px;left:25px;pointer-events:none;position:absolute;width:24px}.wrapper{bottom:0;height:53px;left:11px;overflow:hidden;pointer-events:none;position:absolute;width:52px}.stem{background-color:#999;bottom:14px;height:14px;left:22px;pointer-events:none;position:absolute;width:9px;z-index:1}.shell{border:7px solid #999;border-radius:28px;bottom:27px;height:57px;pointer-events:none;position:absolute;width:38px;z-index:0;left:0px}.s2ml .receiver,.s2ml .stem{background-color:#f44}.s2ml .shell{border-color:#f44}.s2ra .receiver,.s2ra .stem{background-color:#fff}.s2ra .shell{border-color:#fff}</style><span class="receiver"></span>
								<div
								class="wrapper"><span class="stem"></span><span class="shell"></span></div>
						</div>
						</span>
				</div>
				<div class="text-container">
					<style>
					.text-container{pointer-events:none;position:absolute;}.spcht{font-weight:normal;line-height:1.2;opacity:0;pointer-events:none;position:absolute;text-align:left;-webkit-font-smoothing:antialiased;transition:opacity .1s ease-in,margin-left .5s ease-in,top 0s linear 0.218s;left:-44px;top:-.2em;margin-left:44px;font-size:32px;width:460px;}.s2fp .spcht{margin-left:0;opacity:1;transition:opacity .5s ease-out,margin-left .5s ease-out}.spchta{color:var(--JKqx2);cursor:pointer;font-size:18px;font-weight:500;pointer-events:auto;text-decoration:underline}.spch-2l.spcht,.spch-3l.spcht,.spch-4l.spcht{transition:top 0.218s ease-out}.spch-2l.spcht{top:-.6em}.spch-3l.spcht{top:-1.3em}.spch-4l.spcht{top:-1.7em}.s2fp .spch-5l.spcht{top:-2.5em;}
					</style><span class="spcht" style="color:#70757a" id="spchi"></span><span class="spcht"
					style="color:#000" id="spchf"></span></div>
				<div class="google-logo"></div>
		</div>
		<div class="permission-bar">
			<style>
			.permission-bar{margin-top:-100px;opacity:0;pointer-events:none;position:absolute;width:500px;transition:opacity 0.218s ease-in,margin-top .4s ease-in}.s2wfp .permission-bar{margin-top:-300px;opacity:1;transition:opacity .5s ease-out 0.218s,margin-top 0.218s ease-out 0.218s}.permission-bar-gradient{box-shadow:0 1px 0px #4285f4;height:80px;left:0;margin:0;opacity:0;pointer-events:none;position:fixed;right:0;top:-80px;transition:opacity 0.218s,box-shadow 0.218s}.s2wfp .permission-bar-gradient{box-shadow:0 1px 80px #4285f4;opacity:1;pointer-events:none;animation:allow-alert .75s 0 infinite;animation-direction:alternate;animation-timing-function:ease-out;transition:opacity 0.218s,box-shadow 0.218s}@-webkit-keyframes allow-alert {from{opacity:1}to{opacity:.35}}
			</style>
			<div class="permission-bar-gradient"></div>
		</div>
	</div>
	</div>
	</dialog>
	<form action="https://www.google.co.jp/search" autocomplete="off" method="GET" role="search">
		<div jsmodel="b5W85 vNzKHd" jsdata="MuIEvd;_;B1Nv6k">
			<div jscontroller="cnjECf" jsmodel="VYkzu kjkykd EPRt9d LM7wx Qlyryb EtCx8b Ip3Erc L97mud          "
			class="A8SBwf" data-alt="false" data-biboe="false" data-efaql="false" data-hp="true"
			jsdata="LVplcb;_;" jsaction="lX6RWd:w3Wsmc;ocDSvd:duwfG;XmGRxb:mVw6nb;DkpM0b:d3sQLd;IQOavd:dFyQEf;XzZZPe:jI3wzf;Aghsf:AVsnlb;iHd9U:Q7Cnrc;f5hEHe:G0jgYd;vmxUb:j3bJnb;XBqW7:ihYaWc;nTzfpf:YPRawb;R2c5O:LuRugf;qiCkJd:ANdidc;Q3vWPd:FtWxqb;htNNz:SNIJTd;NOg9L:HLgh3;uGoIkd:epUokb;zLdLw:eaGBS;H9muVd:J4e6lb;djyPCf:nMeUJf;hBEIVb:nUZ9le;rcuQ6b:npT2md">
				<style>
				.A8SBwf,.IormK{width:640px;}.A8SBwf{margin:0 auto;width:auto;max-width:584px;padding-top:6px;position:relative}.RNNXgb{display:flex;z-index:3;position:relative;min-height:44px;background:#fff;border:1px solid #dfe1e5;box-shadow:none;border-radius:24px;margin:0 auto;width:638px;width:auto;max-width:584px}.emcav .RNNXgb,.BgPPrc .RNNXgb{border-bottom-left-radius:0;border-bottom-right-radius:0;box-shadow:0 1px 6px rgba(32,33,36,.28);border-color:transparent;}.emcav.emcat .RNNXgb{border-bottom-left-radius:24px;border-bottom-right-radius:24px}.RNNXgb:hover,.sbfc .RNNXgb{background:#fff;box-shadow:0 1px 6px rgba(32,33,36,.28);border-color:transparent}.SDkEP{flex:1;display:flex;padding:0 8px 0 0;}.FPdoLc{padding-top:18px}.emcav.A8SBwf.pD4qTd{z-index:989}.iblpc{display:flex;align-items:center;padding-right:13px;padding-left:14px;height:46px}.M8H8pb{position:absolute;top:0;left:0;right:0;padding:inherit;width:inherit}
				</style>
				<div jsname="RNNXgb" class="RNNXgb">
					<div class="SDkEP">
						<div jsname="uFMOof" class="iblpc">
							<style>
							.CcAdNb{margin:auto}.QCzoEc{margin-top:3px;color:#9aa0a6}
							</style>
							<div class="CcAdNb"><span class="QCzoEc z1asCe MZy1Rb" style="height:20px;line-height:20px;width:20px"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path></svg></span></div>
						</div>
						<div jscontroller="vZr2rb" jsname="gLFyf" class="a4bIc" data-hpmde="false"
						data-mnr="10" jsaction="h5M12e;input:d3sQLd;blur:jI3wzf">
							<style>
							.gLFyf,.ql1tMb,.YacQv{line-height:34px;font-size:16px;flex:100%;}textarea.gLFyf,.ql1tMb,.YacQv{font-family:Arial,sans-serif;line-height:22px;border-bottom:8px solid transparent;padding-top:11px;overflow-x:hidden}textarea.gLFyf{}.sbfc textarea.gLFyf{white-space:pre-line;overflow-y:auto}.gLFyf{resize:none;background-color:transparent;border:none;margin:0;padding:0;color:rgba(0,0,0,.87);word-wrap:break-word;outline:none;display:flex;-webkit-tap-highlight-color:transparent}.a4bIc{display:flex;flex-wrap:wrap;flex:1;}.YacQv{color:transparent;white-space:pre;position:absolute;pointer-events:none}.YacQv span{text-decoration:#b3261e dotted underline}
							</style>
							<div jsname="vdLsw" class="YacQv"></div>
							<textarea class="gLFyf" aria-controls="Alh6id" aria-owns="Alh6id" autofocus=""
							title="検索" value="" jsaction="paste:puy29d;" aria-label="" aria-autocomplete="both"
							aria-expanded="false" aria-haspopup="false" autocapitalize="off" autocomplete="off"
							autocorrect="off" id="APjFqb" maxlength="2048" name="q" role="combobox" rows="1"
							spellcheck="false" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ39UDCAQ"></textarea>
						</div>
						<div class="fM33ce dRYYxd">
							<style>
							.dRYYxd{display:flex;flex:0 0 auto;align-items:stretch;flex-direction:row;height:44px}
							</style>
							<style>
							.BKRPef{background:transparent;align-items:center;flex:1 0 auto;flex-direction:row;display:flex;cursor:pointer}.vOY7J{background:transparent;border:0;align-items:center;flex:1 0 auto;cursor:pointer;display:none;height:100%;line-height:44px;outline:none;padding:0 12px}.M2vV3{display:flex}.ExCKkf{height:100%;color:var(--IXoxUe);vertical-align:middle;outline:none}
							</style>
							<style>
							.BKRPef{padding-right:4px}.ACRAdd{border-left:1px solid #dadce0;height:65%}.ACRAdd{display:none}.ACRAdd.M2vV3{display:block}
							</style>
							<div jscontroller="PymCCe" jsname="RP0xob" class="BKRPef">
								<div class="vOY7J" tabindex="0" jsname="pkjasb" aria-label="消去" role="button"
								jsaction="AVsnlb;rcuQ6b:npT2md" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ05YFCAU">
								<span jsname="itVqKe" class="ExCKkf z1asCe rzyADb"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"></path></svg></span>									</div> <span jsname="s1VaRe" class="ACRAdd"></span> </div>
							<style>
							.XDyW0e{flex:1 0 auto;display:flex;cursor:pointer;align-items:center;border:0;background:transparent;outline:none;padding:0 8px;width:24px;line-height:44px}.goxjub{height:24px;width:24px;vertical-align:middle}
							</style>
							<div jscontroller="unV4T" jsname="F7uqIe" class="XDyW0e" aria-label="音声で検索"
							role="button" tabindex="0" jsaction="h5M12e;rcuQ6b:npT2md" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQvs8DCAY">
								<svg class="goxjub" focusable="false" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
									<path fill="#4285f4" d="m12 15c1.66 0 3-1.31 3-2.97v-7.02c0-1.66-1.34-3.01-3-3.01s-3 1.34-3 3.01v7.02c0 1.66 1.34 2.97 3 2.97z"></path>
									<path fill="#34a853" d="m11 18.08h2v3.92h-2z"></path>
									<path fill="#fbbc04" d="m7.05 16.87c-1.27-1.33-2.05-2.83-2.05-4.87h2c0 1.45 0.56 2.42 1.47 3.38v0.32l-1.15 1.18z"></path>
									<path fill="#ea4335" d="m12 16.93a4.97 5.25 0 0 1 -3.54 -1.55l-1.41 1.49c1.26 1.34 3.02 2.13 4.95 2.13 3.87 0 6.99-2.92 6.99-7h-1.99c0 2.92-2.24 4.93-5 4.93z"></path>
								</svg>
							</div>
							<style>
							.nDcEnd{flex:1 0 auto;display:flex;cursor:pointer;align-items:center;border:0;background:transparent;outline:none;padding:0 8px;width:24px;line-height:44px}.Gdd5U{height:24px;width:24px;vertical-align:middle}
							</style>
							<div jscontroller="lpsUAf" jsname="R5mgy" class="nDcEnd" data-base-lens-url="https://lens.google.com"
							data-image-processor-enabled="true" data-is-images-mode="false" data-preferred-mime-type="image/jpeg"
							data-propagated-experiment-ids="" aria-label="画像で検索" role="button" tabindex="0"
							jsaction="rcuQ6b:npT2md;h5M12e" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQhqEICAc">
								<svg class="Gdd5U" focusable="false" viewBox="0 0 192 192" xmlns="http://www.w3.org/2000/svg">
									<rect fill="none" height="192" width="192"></rect>
									<g>
										<circle fill="#34a853" cx="144.07" cy="144" r="16"></circle>
										<circle fill="#4285f4" cx="96.07" cy="104" r="24"></circle>
										<path fill="#ea4335" d="M24,135.2c0,18.11,14.69,32.8,32.8,32.8H96v-16l-40.1-0.1c-8.8,0-15.9-8.19-15.9-17.9v-18H24V135.2z"></path>
										<path fill="#fbbc04" d="M168,72.8c0-18.11-14.69-32.8-32.8-32.8H116l20,16c8.8,0,16,8.29,16,18v30h16V72.8z"></path>
										<path fill="#4285f4" d="M112,24l-32,0L68,40H56.8C38.69,40,24,54.69,24,72.8V92h16V74c0-9.71,7.2-18,16-18h80L112,24z"></path>
									</g>
								</svg>
							</div>
						</div>
					</div>
				</div>
				<div jscontroller="Dvn7fe" jsname="UUbT9" class="UUbT9 EyBRub" style="display:none"
				jsaction="mouseout:ItzDCd;mouseleave:MWfikb;hBEIVb:nUZ9le;YMFC3:VKssTb;vklu5c:k02QY;ldyIye:CmVOgc"
				data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ4tUDCAg">
					<style>
					.UUbT9{position:absolute;text-align:left;z-index:3;cursor:default;-webkit-user-select:none;width:100%;margin-top:-1px;}.aajZCb{display:flex;flex-direction:column;margin:0;padding:0;overflow:hidden;background:#fff;border-radius:0 0 24px 24px;box-shadow:0 4px 6px rgba(32,33,36,.28);border:0;padding-bottom:4px}.minidiv .aajZCb{border-radius:0 0 16px 16px}.mkHrUc{display:flex}.pD4qTd .rLrQHf{padding-bottom:16px}.pD4qTd .rLrQHf{min-width:47%;width:47%;margin:8px 16px 0}.pD4qTd .rLrQHf:empty{display:none}.erkvQe{padding-bottom:8px;flex:auto;overflow-x:hidden}.RjPuVb{height:1px;margin:0 26px 0 0}.S3nFnd{display:flex}.S3nFnd .RjPuVb,.S3nFnd .aajZCb{flex:0 0 auto}.lh87ke:link,.lh87ke:visited{color:var(--JKqx2);cursor:pointer;font:11px arial,sans-serif;padding:0 5px;text-decoration:none;flex:auto;align-self:flex-end;margin:0 16px 5px 0}.lh87ke:hover{text-decoration:underline}.xtSCL{border-top:1px solid #e8eaed;margin:0 20px 0 14px;padding-bottom:4px}.sb27{background:url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 -21px;background-size:20px;min-height:20px;min-width:20px;height:20px;width:20px}.sb43{background:url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 0;background-size:20px;min-height:20px;min-width:20px;height:20px;width:20px}.sb53.sb53{padding:0 4px;margin:0}.sb33{background:url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 -42px;background-size:20px;height:20px;width:20px;}
					</style>
					<div jscontroller="Wo3n8" jsname="aadvhe" jsmodel="d5EhJe" data-bkt="searchbox"
					data-eas="" data-fhs="" data-maindata="[null,null,null,&quot;autocomplete_user_feedback_kp_id&quot;,null,11,null,null,null,null,null,5010715,&quot;searchbox&quot;,null,&quot;AutocompletePrediction&quot;,null,null,null,null,11]"
					data-pid="5010715" jsdata="vST7rb;_;B1Nv6o zEIyGd;_;" jsaction="kPzEO:MlP2je;qjLxRc:FbhRG;w8f1fc:hRwSgb;kq2wxf:s5CUif;aIJAdf:UhDUnd;BqbTbe:naa5ve;kYAKrf:CqUGrf;hwhRRe:KyxjCd;rcuQ6b:npT2md">
						<div id="_KnDAZtO4CObk2roP-pvLiAs_1">
							<style>
							.z8gr9e{color:var(--bbQxAb)}
							</style>
							<style>
							.i1eWpb .GTERze{display:none}.ky4hfd{display:none}.i1eWpb .ky4hfd{display:block}
							</style>
							<div jsname="GkjeIf" id="_KnDAZtO4CObk2roP-pvLiAs_4" data-jiis="up"
							data-async-type="kp_feedback" class="yp" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ68cECAk"></div>
						</div>
					</div>
					<div jscontroller="P10Owf" class="YB4h9 ky4hfd" aria-label="フィードバックをお送りいただけるものを選択してください"
					jsdata="vST7rb;_;B1Nv6o" role="dialog" jsaction="kPzEO:MlP2je;qjLxRc:MlP2je;w8f1fc:hRwSgb;kq2wxf:s5CUif"
					data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQlokGCAo">
						<div id="_KnDAZtO4CObk2roP-pvLiAs_6">
							<style>
							.YB4h9{background-color:var(--TMYS9);color:var(--EpFNW);padding:18px 60px 18px 12px;position:relative}.C85rO{font-size:20px}.Gtr0ne{padding-top:10px}.zYSLYb{}.YB4h9 .Gtr0ne .zYSLYb{color:var(--EpFNW);text-decoration:underline}.YB4h9 .Job8vb{padding:20px;position:absolute;right:0;top:0}.YB4h9.rPPJbd .Job8vb{padding-top:24px;padding-right:8px;position:absolute;right:0;top:0}.YB4h9.q7XNbb{margin-bottom:44px}.YB4h9.JF7fk{border-radius:16px;border-style:solid;border-color:var(--gS5jXb)}.YB4h9.IPINXd{border-bottom-left-radius:16px;border-bottom-right-radius:16px;border-color:var(--gS5jXb);border-style:solid;border-top:none}.YB4h9.rPPJbd{background-color:var(--xhUGwc);color:var(--bbQxAb)}.YB4h9.rPPJbd .zYSLYb{color:var(--bbQxAb);text-decoration:underline}.R4GmFb{align-items:center;display:flex;flex-direction:row;margin-bottom:8px}.R4GmFb svg{display:block}.JrWcR{margin-left:10px}
							</style><span class="Job8vb z1asCe wuXmqc" aria-label="フィードバックをお送りいただけるものを選択してください を閉じる"
							role="button" tabindex="0" jsaction="kEOk4d" style="height:20px;line-height:20px;width:20px"
							data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQmIkGCAs"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"></path></svg></span>
							<div
							class="C85rO" aria-level="1" role="heading">フィードバックをお送りいただけるものを選択してください</div>
					</div>
				</div>
				<div jsname="RjPuVb" class="RjPuVb"></div>
				<div jsname="aajZCb" class="aajZCb">
					<div class="xtSCL"></div>
					<div class="mkHrUc" id="Alh6id" role="presentation">
						<div jsname="erkvQe" class="erkvQe"></div>
						<div jsname="tovEib" class="rLrQHf" role="presentation"></div>
					</div>
					<style>
					#shJ2Vb{display:none}.OBMEnb{padding:0;margin:0}.G43f7e{display:flex;flex-direction:column;min-width:0;padding:0;margin:0;list-style:none}.Ye4jfc{flex-direction:row;flex-wrap:wrap}
					</style>
					<div jsname="E80e9e" class="OBMEnb" id="shJ2Vb" role="presentation">
						<ul jsname="bw4e9b" class="G43f7e" role="listbox"></ul>
					</div>
					<style>
					#ynRric{display:none}.ynRric{list-style-type:none;flex-direction:column;color:var(--IXoxUe);font-family:Arial,sans-serif-medium,sans-serif;font-size:14px;margin:0 20px 0 16px;padding:8px 0 8px 0;line-height:16px;width:100%}
					</style>
					<div class="ynRric" id="ynRric" role="presentation"></div>
					<style>
					.sbct{display:flex;flex-direction:column;min-width:0;overflow:hidden;padding:0}.eIPGRd{flex:auto;display:flex;align-items:center;margin:0 20px 0 14px}.pcTkSc{display:flex;flex:auto;flex-direction:column;min-width:0;padding:6px 0}.sbic{display:flex;align-items:center;margin:0 13px 0 1px;}.sbic.vYOkbe{background:center/contain no-repeat;border-radius:4px;min-height:32px;min-width:32px;margin:4px 7px 4px -5px}.sbre .wM6W7d{line-height:18px}.ClJ9Yb{line-height:12px;font-size:13px;color:#70757a;margin-top:2px;padding-right:8px}.wM6W7d{display:flex;font-size:16px;color:#212121;flex:auto;align-items:center;word-break:break-word;padding-right:8px}.WggQGd{color:#52188c}.wM6W7d span{flex:auto}.AQZ9Vd{display:flex;align-self:stretch}.sbhl{border-radius:4px;background:#f3f5f6}.UUbT9.i1eWpb .PZPZlf.sbhl{background:none}.UUbT9.i1eWpb .PZPZlf.sbhl .gmlSVb{background:rgba(234,67,53,.12)}@media (forced-colors:active){.sbhl{background-color:highlight}}.mus_pc{display:block;margin:6px 0}.mus_il{font-family:Arial,Helvetica Neue Light,Helvetica Neue,Helvetica;padding-top:7px;position:relative}.mus_il:first-child{padding-top:0}.mus_il_at{margin-left:10px}.mus_il_st{right:52px;position:absolute}.mus_il_i{align:left;margin-right:10px}.mus_it3{margin-bottom:3px;max-height:24px;vertical-align:bottom}.mus_tt3{color:#767676;font-size:12px;vertical-align:top}.mus_tt5{color:#188038;font-size:14px}.mus_tt6{color:#d93025;font-size:14px}.mus_tt8{font-size:16px;font-family:Arial,sans-serif}.mus_tt17{color:#212121;font-size:20px}.mus_tt18{color:#212121;font-size:28px}.mus_tt19{color:#767676;font-size:12px}.mus_tt20{color:#767676;font-size:14px}.mus_tt23{color:#767676;font-size:18px}.TfeWfb{display:none}.xAmryf{display:none}.DJbVFb .TfeWfb{display:flex;flex-wrap:wrap;overflow-x:hidden;width:100%;height:52px}.DJbVFb .AQZ9Vd{display:none}.DJbVFb .xAmryf{border-radius:100px;background-color:var(--xhUGwc)}.DJbVFb .TfeWfb{display:inherit}.DJbVFb .xAmryf .eL7oAc{display:none}.DJbVFb{background:#f8f9fa;border-radius:20px}.DJbVFb:hover{background:#e8eaed}.DJbVFb .vYOkbe{height:-1px;width:-1px;flex-shrink:0;margin:20px 0 20px 8px;float:right;border-radius:16px;background-color:#fff}.DJbVFb.sbhl{background:#e8eaed}.DJbVFb .ClJ9Yb{display:none}.DJbVFb .wM6W7d{flex:initial}.DJbVFb .wM6W7d span{text-overflow:ellipsis;-webkit-box-orient:vertical;display:-webkit-box;-webkit-line-clamp:2;overflow:hidden}.DJbVFb .eIPGRd{display:flex;flex-direction:row-reverse;align-items:stretch;margin:0 20px 0 14px}.DJbVFb .a5RLac{line-height:24px;font-size:20px;font-family:Arial,sans-serif;padding-top:16px;color:var(--bbQxAb);margin-bottom:auto}.DJbVFb.ytLedb .vYOkbe{background-color:#f8f9fa}.DJbVFb .kzCE2{font-size:16px}.DJbVFb .wM6W7d span{color:var(--YLNNHc);line-height:36px;font-weight:400;font-size:28px;font-family:Arial,sans-serif}.DJbVFb .pcTkSc{margin:20px 6px;padding:0}.DJbVFb .vYOkbe{margin:20px 0 20px 18px;background-color:#fff;border-radius:20px}.DJbVFb .EOLKOc{width:calc(50% - 1px)}.iQxPRb{display:flex;gap:2px}.DJbVFb .EOLKOc:first-child{border-bottom-left-radius:20px}.DJbVFb .EOLKOc:last-child{border-bottom-right-radius:20px}.DJbVFb .AZNDm{border-top-right-radius:20px;border-top-left-radius:20px}.DJbVFb .a5RLac.kzCE2 span{-webkit-line-clamp:3}.DJbVFb .lnnVSe{margin-bottom:auto}.DJbVFb .a5RLac span{text-overflow:ellipsis;-webkit-box-orient:vertical;display:-webkit-box;-webkit-line-clamp:2;overflow:hidden;margin-right:10px}#bgeLZd{display:none}.xAmryf{box-sizing:border-box;align-items:center;height:40px;border-radius:8px;display:flex;color:var(--bbQxAb);border:1px solid var(--mXZkqc);background-color:var(--xhUGwc);line-height:22px}.xAmryf .eL7oAc{fill:var(--bbQxAb);padding-top:1px}.xAmryf.LvqzR{background-color:#e8f0fe;cursor:pointer;color:var(--TMYS9)}.xAmryf.LvqzR .eL7oAc{fill:var(--TMYS9)}.jtAOgd{white-space:nowrap;font-family:Arial,sans-serif;font-size:14px;margin:0 14px}.TfeWfb{gap:12px 6px;overflow-x:auto;-ms-overflow-style:none;scrollbar-width:none}.TfeWfb::-webkit-scrollbar{display:none}.uhebGb{font-style:italic}#YMXe{display:none}
					</style>
					<li data-view-type="1" class="sbct PZPZlf" id="YMXe" role="presentation"
					data-attrid="AutocompletePrediction" data-entityid="autocomplete_user_feedback_kp_id">
						<div class="eIPGRd">
							<div class="sbic">
								<div class="j0GJWd" style="display:none">
									<div><img class="uHGFVd AZNDm" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_2"
										data-atf="0"></div>
									<div class="iQxPRb"><img class="uHGFVd EOLKOc" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_3"
										data-atf="0"><img class="uHGFVd EOLKOc" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_4"
										data-atf="0"></div>
								</div>
							</div>
							<div class="pcTkSc">
								<div class="lnnVSe" aria-atomic="true" role="option">
									<div class="wM6W7d"><span></span></div>
									<div class="ClJ9Yb"><span></span></div>
									<div class="a5RLac"><span></span></div>
								</div>
								<style>
								.MagqMc .ZFiwCf{background-color:#fff;border:1px solid var(--gS5jXb);width:100%}.MagqMc.U48fD{padding:0;margin-top:16px}.MagqMc .Bi9oQd{display:none}.MagqMc{padding:0}.MagqMc:hover .LGwnxb{color:var(--YLNNHc)}.sOmPcf .ZFiwCf{background-color:#fafafa}
								</style>
								<div class="Sz7Lee MagqMc U48fD" style="display:none" aria-label="もっと見る"
								role="button" tabindex="0">
									<style>
									.U48fD{-webkit-tap-highlight-color:transparent;cursor:pointer;display:block;line-height:18px;text-overflow:ellipsis;white-space:nowrap;padding:16px;padding-top:0;margin-top:24px;position:relative}.TQc1id .U48fD{margin-top:16px}.U48fD.df13ud{margin-top:16px}.U48fD.TOQyFc{margin-top:0}.U48fD.p8FEIf{padding-bottom:0}.U48fD.ke7M4{padding-left:0;padding-right:0}.jRKCUd::before{bottom:12px;content:'';left:16px;position:absolute;right:16px;top:-4px}a.jRKCUd:hover{text-decoration:none}
									</style>
									<style>
									.ZFiwCf{display:flex;align-items:center;justify-content:center;position:relative;margin:0 auto;width:100%;border-radius:18px;outline:1px solid transparent;background-color:#f1f3f4;font-size:14px;font-family:Arial,sans-serif;font-weight:400;max-width:300px;height:36px}@media (forced-colors:active){.ZFiwCf{border:1px solid transparent}}.TQc1id .ZFiwCf{max-width:unset}.Zjtggb .ZFiwCf{max-width:unset}.ZFiwCf:hover{background-color:#fafafa}.nCFUpc .ZFiwCf{width:100%}.Bi9oQd{background-color:var(--gS5jXb);margin-top:18px;position:absolute;border:0;height:1px;left:0;width:100%;}.TQc1id .Bi9oQd{display:none}.kC8B4e .Bi9oQd{display:none}.w2fKdd svg{width:auto}.w2fKdd{color:#5e5e5e}.LGwnxb{overflow:hidden;text-overflow:ellipsis;white-space:nowrap;width:auto;padding-left:0;padding-right:8px;max-width:calc(100% - 64px);color:#202124}.LGwnxb:empty{padding-right:0}.LGwnxb span,.LGwnxb div{overflow:hidden;text-overflow:ellipsis;white-space:nowrap;width:auto}
									</style>
									<hr class="Bi9oQd" aria-hidden="true">
									<div class="ZFiwCf"><span class="LGwnxb">もっと見る</span><span class="w2fKdd z1asCe" aria-hidden="true"
										style="height:20px;line-height:20px;width:20px"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l-1.41 1.41L16.17 11H4v2h12.17l-5.58 5.59L12 20l8-8z"></path></svg></span></div>
								</div>
							</div>
							<div class="AQZ9Vd" aria-atomic="true" role="button">
								<style>
								.JCHpcb:hover,.LvqzR .JCHpcb{color:#1558d6;text-decoration:underline}.JCHpcb{color:#70757a;font:13px arial,sans-serif;cursor:pointer;align-self:center}@media (hover:hover){.sbai{visibility:hidden}.sbhl .sbai{visibility:inherit}}
								</style>
								<div class="sbai" role="presentation">削除</div>
							</div>
						</div>
					</li>
					<style>
					#d6ItKb{display:none}.AB2Fdd{display:flex}
					</style>
					<li class="AB2Fdd" data-view-type="9" id="d6ItKb" role="presentation">
						<div class="eIPGRd">
							<div class="ZDHp" style="display:none" id="fU0xAb" role="presentation">
								<div class="kZtr1b">
									<style>
									.ZDHp{position:relative;margin:20px;display:flex}.DJbVFb,.o6OF0{background:#f8f9fa;border-radius:20px}.o6OF0:hover,.o6OF0.LvqzR{background:#e7e8e9}.o6OF0 .eIPGRd{display:block}@media (forced-colors:none){.o6OF0.sbhl{background:#e7e8e9}}@media (forced-colors:active){.o6OF0.sbhl{background-color:highlight}}.o6OF0 .AQZ9Vd{display:none}.o6OF0 .sbic{display:none}.o6OF0 .pcTkSc{display:none}.o6OF0 .wM6W7d{display:none}.o6OF0 .eIPGRd{max-width:100%;margin:0}.az9Ajc{padding_top:0px}.ZDHp .SHFPkb{margin-bottom:12px}.o6OF0 .SHFPkb{line-height:48px;font-family:Arial,sans-serif;font-size:36px;font-weight:400;color:var(--YLNNHc);display:-webkit-box;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical}.lQoozf{font-size:28px}.o6OF0 .SHFPkb.ZJ594e{padding-right:58px}.o6OF0 .HrUlUc,.o6OF0 .PnfqLc{font-family:Arial,sans-serif;font-weight:400;max-height:72px;color:var(--bbQxAb)}.ZDHp .HrUlUc,.ZDHp .PnfqLc{font-size:18px;line-height:24px}.o6OF0 .bTSf5c{font-family:Arial,sans-serif;font-weight:400;color:var(--bbQxAb)}.ZDHp .bTSf5c{line-height:22px;font-size:14px;margin-bottom:6px}.ZDHp .HrUlUc,.ZDHp .PnfqLc{overflow:hidden;display:-webkit-box;-webkit-line-clamp:3;-webkit-box-orient:vertical}.Vlt3wb{font-style:normal;font-family:Arial,sans-serif;font-weight:400;font-size:14px;line-height:22px;padding-top:8px;margin-top:12px;color:var(--bbQxAb);border-top:1px solid #dadce0;display:flex;width:100%}.Tnv2td{position:absolute;top:0;right:0}.z76Rnb{padding:6px;width:24px;height:24px;background-color:var(--xhUGwc);color:#5e5e5e;border-radius:9999px;border:1px solid var(--mXZkqc);cursor:pointer}.z76Rnb.LvqzR{color:var(--YLNNHc);background-color:#fafafa}.kZtr1b{display:flex;flex-direction:column;flex-grow:1;min-width:0}.XAFD5c{width:200px;height:200px;background-color:var(--xhUGwc);border-radius:20px;margin-left:20px;flex-shrink:0;background-position:center;background-repeat:no-repeat;background-size:contain}.XAFD5c.iNF0Vd{background-size:136px}.ZDHp .lnnVSe{font-size:18px;flex-grow:1}.ZDHp .HrUlUc,.ZDHp .PnfqLc{display:flex;flex-direction:column}.rnAixd{color:#b3261e}.izxCJf{color:#146c2e}
									</style>
									<div class="lnnVSe" aria-atomic="true" role="option">
										<div class="SHFPkb"></div>
										<div class="bTSf5c"></div>
										<div class="PnfqLc"></div>
										<div class="HrUlUc"></div>
									</div>
									<div class="Tnv2td" aria-atomic="true" role="button" style="display:none"><span class="z76Rnb z1asCe JKu1je"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path></svg></span></div>
									<div
									class="Vlt3wb" style="display:none"></div>
							</div><span class="XAFD5c" style="display:none"></span>
							<div class="j0GJWd" style="display:none">
								<div><img class="uHGFVd AZNDm" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_5"
									data-atf="0"></div>
								<div class="iQxPRb"><img class="uHGFVd EOLKOc" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_6"
									data-atf="0"><img class="uHGFVd EOLKOc" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_7"
									data-atf="0"></div>
							</div>
						</div>
				</div>
				</li>
				<style>
				#mitGyb{display:none}.s2Wjec{display:block}.Q82Okf{font-size:16px;font-family:Arial,sans-serif}
				</style>
				<li data-view-type="8" class="sbct PZPZlf" id="mitGyb" role="presentation"
				data-attrid="AutocompletePrediction" data-entityid="autocomplete_user_feedback_kp_id">
					<div class="eIPGRd hdt0ld">
						<div class="sbic"></div>
						<div class="pcTkSc">
							<div aria-atomic="true" class="lnnVSe" role="option">
								<div class="wM6W7d"><span></span></div>
								<div class="ClJ9Yb"><span></span></div>
							</div>
						</div>
						<div class="AQZ9Vd" aria-atomic="true" role="button">
							<div class="sbai" role="presentation">削除</div>
						</div>
					</div>
				</li>
				<div class="ZDHp" style="display:none" id="fU0xAb" role="presentation">
					<div class="kZtr1b">
						<div class="lnnVSe" aria-atomic="true" role="option">
							<div class="SHFPkb"></div>
							<div class="bTSf5c"></div>
							<div class="PnfqLc"></div>
							<div class="HrUlUc"></div>
						</div>
						<div class="Tnv2td" aria-atomic="true" role="button" style="display:none"><span class="z76Rnb z1asCe JKu1je"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path></svg></span></div>
						<div
						class="Vlt3wb" style="display:none"></div>
				</div><span class="XAFD5c" style="display:none"></span>
				<div class="j0GJWd" style="display:none">
					<div><img class="uHGFVd AZNDm" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_8"
						data-atf="0"></div>
					<div class="iQxPRb"><img class="uHGFVd EOLKOc" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_9"
						data-atf="0"><img class="uHGFVd EOLKOc" alt="" style="display:none" data-csiid="KnDAZtO4CObk2roP-pvLiAs_10"
						data-atf="0"></div>
				</div>
			</div>
			<style>
			#TN4rFf{display:none}.IDVnvc{display:inline-block;overflow:hidden;max-width:223px;border-radius:16px;height:178px;margin:-2px -10px 2px 10px}.IDVnvc.sbhl{border-radius:16px}.OBMEnb:only-child .IDVnvc{margin-right:calc(25% - 113px)}.cRV9hb{width:90px;padding:6px}.cRV9hb .pcTkSc{font-family:Arial,sans-serif;overflow:hidden;margin-top:4px;padding:0}.cRV9hb .pcTkSc .wM6W7d{font-size:14px;line-height:18px;padding:0;color:var(--COEmY)}.cRV9hb .pcTkSc .ClJ9Yb{line-height:16px;font-size:12px;display:none;display:flex}.cRV9hb .pcTkSc .ClJ9Yb.ENMKxf span{-webkit-line-clamp:1}.cRV9hb .pcTkSc .wM6W7d span,.cRV9hb .pcTkSc .ClJ9Yb span{overflow:hidden;text-overflow:ellipsis;-webkit-box-orient:vertical;display:-webkit-box;white-space:normal}.cRV9hb .pcTkSc .wM6W7d span{-webkit-line-clamp:2}.cRV9hb .pcTkSc .ClJ9Yb span{-webkit-line-clamp:2}.aVbWac{background:#fff;border-radius:12px;height:90px}.aVbWac .sbic.vYOkbe{height:90px;width:90px;border-radius:12px;margin:0}
			</style>
			<li class="IDVnvc PZPZlf" data-view-type="6" id="TN4rFf" role="presentation"
			data-attrid="AutocompletePrediction" data-entityid="autocomplete_user_feedback_kp_id">
				<div class="cRV9hb">
					<div class="aVbWac">
						<div class="sbic"></div>
					</div>
					<div class="pcTkSc" role="presentation">
						<div class="lnnVSe" aria-atomic="true" role="option">
							<div class="wM6W7d"><span></span></div>
							<div class="ClJ9Yb"><span></span></div>
						</div>
					</div>
				</div>
			</li>
			<div jsname="VlcLAe" class="lJ9FBc">
				<style>
				.lJ9FBc{height:70px}.lJ9FBc input[type="submit"],.gbqfba{background-color:#f8f9fa;border:1px solid #f8f9fa;border-radius:4px;color:#3c4043;font-family:Arial,sans-serif;font-size:14px;margin:11px 4px;padding:0 16px;line-height:27px;height:36px;min-width:54px;text-align:center;cursor:pointer;user-select:none}.lJ9FBc input[type="submit"]:hover{box-shadow:0 1px 1px rgba(0,0,0,.1);background-color:#f8f9fa;border:1px solid #dadce0;color:#202124}.lJ9FBc input[type="submit"]:focus{border:1px solid #4285f4;outline:none}
				</style>
				<center>
					<input class="gNO89b" value="Google 検索" aria-label="Google 検索" name="btnK" role="button"
					tabindex="0" type="submit" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ4dUDCA0">
					<input class="RNmpXc" value="I&#39;m Feeling Lucky" aria-label="I&#39;m Feeling Lucky"
					name="btnI" type="submit" jsaction="trigger.kWlxhc" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ19QECA4"> </center>
			</div>
		</div>
		<div jsname="JUypV">
			<style>
			.WzNHm{font-size:11px;font-style:italic;margin-top:-16px;position:absolute;right:20px;color:var(--IXoxUe)}
			</style>
			<div class="WzNHm mWcf0e" jscontroller="gSZvdb" data-dccl="false" role="button"
			tabindex="0" jsdata="vST7rb;_;B1Nv6o" jsaction="i5KCU;kVBCVd:yM1YJe" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ6scECA8">
				<div class="VfL2Y LRZwuc">不適切な検索候補の報告</div>
			</div>
		</div>
		</div>
		<div jsname="mvaK7d" class="M8H8pb" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ4d8ICBA"></div>
		<div class="FPdoLc lJ9FBc">
			<center>
				<input class="gNO89b" value="Gooooooogle 検索" aria-label="Google 検索" name="btnK" role="button"
				tabindex="0" type="submit" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ4dUDCBE">
				<input id="gbqfbb" value="I&#39;m Feeling Lucky" aria-label="I&#39;m Feeling Lucky"
				name="btnI" role="button" tabindex="0" type="submit" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQnRsIEg">
				<div class="gbqfba gbqfba-hvr" role="button" style="display: none; font-family: Arial, sans-serif; overflow: hidden; text-align: center; z-index: 50;">
					<div style="left: 0px; position: absolute; right: 0px; white-space: nowrap;">
						<div role="presentation"><span>お腹がすいた</span></div>
						<div role="presentation"><span>冒険したい</span></div>
						<div role="presentation"><span>遊びたい気分</span></div>
						<div role="presentation"><span>星になった気分</span></div>
						<div role="presentation"><span>Doodle を探そう</span></div>
						<div role="presentation"><span>トレンディーな気分</span></div>
						<div role="presentation"><span>芸術家気分</span></div>
						<div role="presentation"><span>笑いたい気分</span></div>
					</div>
				</div>
			</center>
		</div>
		</div>
		<div style="background:url(/images/searchbox/desktop_searchbox_sprites318_hr.webp)">
		</div>
		<script nonce="">
		(function() {
			var a = this || self;
			var c = document.querySelector("form");
			if (c) {
				var d = function(b) {
					b.key !== "Enter" || b.shiftKey || (b.preventDefault(), c.submit && c.submit())
				};
				c.addEventListener("keydown", d);
				a.sbmlhf = d
			};
		}).call(this);

		</script>
		</div>
		<div id="tophf">
			<input name="sca_esv" value="3efbb99c78a025e4" type="hidden">
			<input name="sca_upv" value="1" type="hidden">
			<input name="source" type="hidden" value="hp">
			<input value="KnDAZtO4CObk2roP-pvLiAs" name="ei" type="hidden">
			<input value="AL9hbdgAAAAAZsB-OmdKaeminbhGcKl49blCJOX4Qa9a" name="iflsig" type="hidden">
		</div>
	</form>
	</div>
	<div class="o3j99 qarstb">
		<style>
		.vcVZ7d{text-align:center}
		</style>
		<div>
			<div jscontroller="ms4mZb" jsname="FAeNCb" data-aipm="0" data-endpoint="1" id="_KnDAZtO4CObk2roP-pvLiAs_8"
			data-jiis="up" data-async-type="hpba" class="yf" jsaction="rcuQ6b:npT2md" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQj-0KCBM"
			eid="LHDAZonGDPve2roPqZOW2Qw">
				<div jsname="Nll0ne"></div>
			</div>
		</div>
	</div>
	<div jscontroller="B2qlPe" jsname="cgsKlb" jsaction="rcuQ6b:npT2md">
		<style>
		.ceE3R{opacity:0.06;pointer-events:none}
		</style>
	</div>
	<div class="o3j99 c93Gbe" role="contentinfo">
		<style>
		.c93Gbe{background:#f2f2f2}.uU7dJb{padding:15px 30px;border-bottom:1px solid var(--gS5jXb);font-size:15px;color:var(--YLNNHc);display:flex;flex-wrap:wrap;justify-content:space-between}.Wymece{justify-content:flex-end}.SSwjIe{padding:0 20px}.KxwPGc{display:flex;flex-wrap:wrap;justify-content:space-between}@media only screen and (max-width:1200px){.KxwPGc{justify-content:space-evenly}}.pHiOh{display:block;padding:15px;white-space:nowrap}.pHiOh,a.pHiOh{color:var(--YLNNHc)}
		</style>
		<div class="uU7dJb">日本</div>
		<div jscontroller="NzU6V" class="KxwPGc SSwjIe" data-sfe="false" data-sfsw="1200"
		jsaction="rcuQ6b:npT2md">
			<div class="KxwPGc AghGtd"><a class="pHiOh" href="https://about.google/?utm_source=google-JP&amp;utm_medium=referral&amp;utm_campaign=hp-footer&amp;fg=1"
				data-jsarwt="1" data-usg="AOvVaw23tpb_gao_ALrHWAX80Ryc" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQkNQCCBQ">Googleについて</a>
				<a
				class="pHiOh" href="https://www.google.co.jp/intl/ja_jp/ads/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&amp;utm_source=google.com&amp;utm_medium=referral&amp;utm_campaign=google_hpafooter&amp;fg=1"
				data-jsarwt="1" data-usg="AOvVaw0e_raBz7SAPOoZMGRYQ2f0" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQkdQCCBU">広告</a><a class="pHiOh" href="https://www.google.co.jp/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&amp;utm_source=google.com&amp;utm_medium=referral&amp;utm_campaign=google_hpbfooter&amp;fg=1"
					data-jsarwt="1" data-usg="AOvVaw313mutxJVym36y7taNTcGC" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQktQCCBY">ビジネス</a>
					<a
					class="pHiOh" href="https://google.com/search/howsearchworks/?fg=1"> 検索の仕組み </a>
			</div>
			<div class="KxwPGc iTjxkf"><a class="pHiOh" href="https://policies.google.com/privacy?hl=ja&amp;fg=1" data-jsarwt="1"
				data-usg="AOvVaw1kGoNKpK-GAHWn7Nc8kYUh" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ8awCCBc">プライバシー</a>
				<a
				class="pHiOh" href="https://policies.google.com/terms?hl=ja&amp;fg=1" data-jsarwt="1"
				data-usg="AOvVaw2RDDrF9T_OwPPXAmUEe2mu" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQ8qwCCBg">規約</a><span><style>.ayzqOc:hover{text-decoration:underline}</style><span jscontroller="nabPbb" data-ffp="false" jsaction="KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;"><style>.cF4V5c{background-color:var(--xhUGwc)}.cF4V5c g-menu-item{display:block;font-size:14px;line-height:23px;white-space:nowrap}.cF4V5c g-menu-item a,.cF4V5c .y0fQ9c{display:block;padding-top:4px;padding-bottom:4px;cursor:pointer}.cF4V5c g-menu-item a,.cF4V5c g-menu-item a:visited,.cF4V5c g-menu-item a:hover{text-decoration:inherit;color:inherit}</style><g-popup jsname="V68bde" jscontroller="DPreE" jsaction="A05xBd:IYtByb;EOZ57e:WFrRFb;" jsdata="mVjAjf;_;B1Nv6s"><div jsname="oYxtQd" class="CcNe6e" aria-expanded="false" aria-haspopup="true" role="button" tabindex="0" jsaction="WFrRFb;keydown:uYT2Vb"><div jsname="LgbsSe" class="ayzqOc pHiOh" aria-controls="_KnDAZtO4CObk2roP-pvLiAs_9" aria-haspopup="true">設定</div></div><div jsname="V68bde" class="UjBGL pkWBse iRQHZe" style="display:none;z-index:200"><g-menu jsname="xl07Ob" class="cF4V5c yTik0 PBn44e iQXTJe wplJBd" jscontroller="WlNQGd" role="menu" tabindex="-1" jsaction="PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c"><g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe" role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w"><div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none"><a href="https://www.google.co.jp/preferences?hl=ja&amp;fg=1" role="menuitem" tabindex="-1">検索設定</a></div></g-menu-item><g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe" role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w"><div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none"><a href="https://www.google.co.jp/advanced_search?hl=ja&amp;fg=1" role="menuitem" tabindex="-1">検索オプション</a></div></g-menu-item><g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe" role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w"><div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none"><a href="https://www.google.co.jp/history/privacyadvisor/search/unauth?utm_source=googlemenu&amp;fg=1&amp;cctld=co.jp" role="menuitem" tabindex="-1">検索におけるデータ</a></div></g-menu-item><g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe" role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w"><div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none"><a href="https://www.google.co.jp/history/optout?hl=ja&amp;fg=1" role="menuitem" tabindex="-1">検索履歴</a></div></g-menu-item><g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe" role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w"><div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none"><a href="https://support.google.com/websearch/?p=ws_results_help&amp;hl=ja&amp;fg=1" role="menuitem" tabindex="-1">ヘルプを検索</a></div></g-menu-item><g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe" role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w"><div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none"><span data-bucket="websearch" role="menuitem" tabindex="-1" jsaction="trigger.YcfJ">フィードバックを送信</span></div>
			</g-menu-item>
			<g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe LGiluc"
			aria-hidden="true" role="separator" data-short-label="" jsdata="zPXzie;_;B1Nv60"></g-menu-item>
			<g-menu-item jsname="NNJLud" jscontroller="CnSW2d" class="EpPYLd GZnQqe"
			role="none" data-short-label="" jsdata="zPXzie;_;B1Nv6w">
				<div jsname="ibnC6b" class="YpcDnf OSrXXb HG1dvd" role="none">
					<div class="y0fQ9c" data-spl="/setprefs?hl=ja&amp;prev=https://www.google.co.jp/?pccc%3D1&amp;sig=0_6BMaq_zTvg8uMrbscQz5E-PW-Kw%3D&amp;cs=2"
					id="YUIDDb" role="menuitem" tabindex="-1">
						<style>
						.tFYjZe{align-items:center;display:flex;justify-content:space-between;padding-bottom:4px;padding-top:4px}.tFYjZe:hover .iOHNLb,.tFYjZe:focus .iOHNLb{opacity:1}.iOHNLb{color:#5e5e5e;height:20px;margin-top:-2px;opacity:0;width:20px}
						</style>
						<div jscontroller="fXO0xe" class="tFYjZe" data-bsdm="0" data-btf="0"
						data-hbc="#1a73e8" data-htc="#fff" data-spt="1" data-tsdm="0" role="link" tabindex="0"
						jsaction="ok5gFc;x6BCfb:ggFCce;w3Ukrf:aelxJb" data-ved="0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQqsEHCBs">
							<div>ダークモード: オフ</div>
							<div class="iOHNLb"><span style="height:20px;line-height:20px;width:20px" class="z1asCe aqvxcd"><svg focusable="false" xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="24" viewBox="0 0 24 24" width="24"><rect fill="none" height="24" width="24"></rect><path d="M12,7c-2.76,0-5,2.24-5,5s2.24,5,5,5s5-2.24,5-5S14.76,7,12,7L12,7z M2,13l2,0c0.55,0,1-0.45,1-1s-0.45-1-1-1l-2,0 c-0.55,0-1,0.45-1,1S1.45,13,2,13z M20,13l2,0c0.55,0,1-0.45,1-1s-0.45-1-1-1l-2,0c-0.55,0-1,0.45-1,1S19.45,13,20,13z M11,2v2 c0,0.55,0.45,1,1,1s1-0.45,1-1V2c0-0.55-0.45-1-1-1S11,1.45,11,2z M11,20v2c0,0.55,0.45,1,1,1s1-0.45,1-1v-2c0-0.55-0.45-1-1-1 C11.45,19,11,19.45,11,20z M5.99,4.58c-0.39-0.39-1.03-0.39-1.41,0c-0.39,0.39-0.39,1.03,0,1.41l1.06,1.06 c0.39,0.39,1.03,0.39,1.41,0s0.39-1.03,0-1.41L5.99,4.58z M18.36,16.95c-0.39-0.39-1.03-0.39-1.41,0c-0.39,0.39-0.39,1.03,0,1.41 l1.06,1.06c0.39,0.39,1.03,0.39,1.41,0c0.39-0.39,0.39-1.03,0-1.41L18.36,16.95z M19.42,5.99c0.39-0.39,0.39-1.03,0-1.41 c-0.39-0.39-1.03-0.39-1.41,0l-1.06,1.06c-0.39,0.39-0.39,1.03,0,1.41s1.03,0.39,1.41,0L19.42,5.99z M7.05,18.36 c0.39-0.39,0.39-1.03,0-1.41c-0.39-0.39-1.03-0.39-1.41,0l-1.06,1.06c-0.39,0.39-0.39,1.03,0,1.41s1.03,0.39,1.41,0L7.05,18.36z"></path></svg></span></div>
						</div>
					</div>
				</div>
			</g-menu-item>
			</g-menu>
		</div>
		</g-popup>
		</span>
		</span>
	</div>
	</div>
	<div jscontroller="zGLm3b" style="display:none" data-pcs="0" jsaction="rcuQ6b:npT2md"></div>
	</div>
	</div>
	<div class="Fgvgjc">
		<style>
		.Fgvgjc{height:0;overflow:hidden}
		</style>
		<div class="gTMtLb fp-nh" id="lb">
			<style>
			.gTMtLb{z-index:1001;position:absolute;top:-1000px}
			</style>
		</div><span style="display:none"><span jscontroller="DhPYme" style="display:none" data-atsd="10" data-db="1" data-mmcnt="100" jsaction="rcuQ6b:npT2md" data-ei="KnDAZtO4CObk2roP-pvLiAs"></span></span>
		<script
		nonce="">this.gbar_=this.gbar_||{};(function(_){var window=this; try{ _.Fd=function(a,b,c){if(!a.j)if(c
			instanceof Array)for(var d of c)_.Fd(a,b,d);else{d=(0,_.z)(a.C,a,b);const e=a.v+c;a.v++;b.dataset.eqid=e;a.B[e]=d;b&&b.addEventListener?b.addEventListener(c,d,!1):b&&b.attachEvent?b.attachEvent("on"+c,d):a.o.log(Error("z`"+b))}};
			}catch(e){_._DumpException(e)} try{ var Gd=document.querySelector(".gb_k .gb_d"),Hd=document.querySelector("#gb.gb_Pc");Gd&&!Hd&&_.Fd(_.pd,Gd,"click");
			}catch(e){_._DumpException(e)} try{ _.Ah=function(a){const b=[];let c=0;for(const
			d in a)b[c++]=a[d];return b};_.Bh=function(a){if(a.v)return a.v;for(const b in
			a.i)if(a.i[b].ma()&&a.i[b].B())return a.i[b];return null};_.Ch=function(a,b){a.i[b.K()]=b};var
			Dh=new class extends _.R{constructor(){var a=_.Zc;super();this.B=a;this.v=null;this.o={};this.C={};this.i={};this.j=null}A(a){this.i[a]&&(_.Bh(this)&&_.Bh(this).K()==a||this.i[a].P(!0))}Ua(a){this.j=a;for(const
			b in this.i)this.i[b].ma()&&this.i[b].Ua(a)}kc(a){return a in this.i?this.i[a]:null}};_.sd("dd",Dh);
			}catch(e){_._DumpException(e)} try{ _.Ti=function(a,b){return _.M(a,36,b)}; }catch(e){_._DumpException(e)}
			try{ var Ui=document.querySelector(".gb_b .gb_d"),Vi=document.querySelector("#gb.gb_Pc");Ui&&!Vi&&_.Fd(_.pd,Ui,"click");
			}catch(e){_._DumpException(e)} })(this.gbar_); // Google Inc. this.gbar_=this.gbar_||{};(function(_){var
			window=this; try{ var Id;Id=class extends _.td{};_.Jd=function(a,b){if(b in a.i)return
			a.i[b];throw new Id;};_.Kd=function(a){return _.Jd(_.qd.i(),a)}; }catch(e){_._DumpException(e)}
			try{ /* SPDX-License-Identifier: Apache-2.0 */ var Qd,$d;_.Ld=function(a){if(a==null)return
			a;if(typeof a==="string"){if(!a)return;a=+a}if(typeof a==="number")return Number.isFinite(a)?a|0:void
			0};_.Md=function(a){const b=a.length;if(b>0){const c=Array(b);for(let d=0;d
			<b;d++)c[d]=a[d];return
			c}return[]};_.Od=function(a){if(a instanceof _.Nd)return a.i;throw Error( "D");};Qd=function(a){return
			new Pd(b=>b.substr(0,a.length+1).toLowerCase()===a+":")}; _.Sd=function(a,b=_.Rd){if(a instanceof
				_.Nd)return a;for(let c=0;c
				<b.length;++c){const d=b[c];if(d instanceof Pd&&d.Wg(a))return
				new _.Nd(a)}};_.Ud=function(a){if(Td.test(a))return a};_.Vd=function(a){return
				a instanceof _.Nd?_.Od(a):_.Ud(a)};_.Wd=function(a,b){var c=Array.prototype.slice.call(arguments,1);return
				function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}};_.Xd=function(a,b,c){return
				_.ub(a,b,c,!1)!==void 0};_.Yd=function(a,b){return _.Ld(_.Nc(a,b))}; _.S=function(a,b){a=_.Nc(a,b);return
				a==null?a:Number.isFinite(a)?a|0:void 0};_.T=function(a,b,c=0){return _.vb(_.Yd(a,b),c)};_.Zd=function(a,b,c=0){return
				_.vb(_.S(a,b),c)};$d=function(a){return a};_.ae=function(a){var b=null,c=_.t.trustedTypes;if(!c||!c.createPolicy)return
				b;try{b=c.createPolicy(a,{createHTML:$d,createScript:$d,createScriptURL:$d})}catch(d){_.t.console&&_.t.console.error(d.message)}return
				b};_.be=function(a,b){return a.lastIndexOf(b,0)==0}; _.ce=function(a,b){return
				Array.prototype.some.call(a,b,void 0)};var de;_.ee=function(){de===void 0&&(de=_.ae(
				"ogb-qtm#html"));return de};var he;_.fe=class{constructor(a){this.i=a}toString(){return this.i+
				""}};_.ge=function(a){return a instanceof _.fe&&a.constructor===_.fe?a.i:
				"type_error:TrustedResourceUrl"};he={};_.ie=function(a){const b=_.ee();a=b?b.createScriptURL(a):a;return new
				_.fe(a,he)};_.Nd=class{constructor(a){this.i=a}toString(){return this.i}};_.je=new
				_.Nd( "about:invalid#zClosurez");var Pd,Td;Pd=class{constructor(a){this.Wg=a}};_.Rd=[Qd(
				"data"),Qd( "http"),Qd( "https"),Qd( "mailto"),Qd( "ftp"),new Pd(a=>/^[^:]*([/?#]|$)/.test(a))];Td=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;_.ke={};_.le=class{constructor(a){this.i=a}toString(){return
					this.i.toString()}};_.me=new _.le("",_.ke);_.ne=RegExp("^[-+,.\"'%_!#/ a-zA-Z0-9\\[\\]]+$");_.oe=RegExp("\\b(url\\([
					\t\n]*)('[ -&(-\\[\\]-~]*'|\"[ !#-\\[\\]-~]*\"|[!#-&*-\\[\\]-~]*)([ \t\n]*\\))","g");_.pe=RegExp("\\b(calc|cubic-bezier|fit-content|hsl|hsla|linear-gradient|matrix|minmax|radial-gradient|repeat|rgb|rgba|(rotate|scale|translate)(X|Y|Z|3d)?|steps|var)\\([-+*/0-9a-zA-Z.%#\\[\\],
					]+\\)","g");_.qe={};_.se=function(a){return a instanceof _.re&&a.constructor===_.re?a.i:"type_error:SafeHtml"};_.re=class{constructor(a){this.i=a}toString(){return
					this.i.toString()}};_.te=new _.re(_.t.trustedTypes&&_.t.trustedTypes.emptyHTML||"",_.qe);_.ue=function(a){let
					b=!1,c;return function(){b||(c=a(),b=!0);return c}}(function(){var a=document.createElement("div"),b=document.createElement("div");b.appendChild(document.createElement("div"));a.appendChild(b);b=a.firstChild.firstChild;a.innerHTML=_.se(_.te);return!b.parentElement});_.ve=function(a,b){this.width=a;this.height=b};_.n=_.ve.prototype;_.n.aspectRatio=function(){return
					this.width/this.height};_.n.Bb=function(){return!(this.width*this.height)};_.n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return
					this};_.n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return
					this};_.n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return
					this};_.U=function(a,b){var c=b||document;if(c.getElementsByClassName)a=c.getElementsByClassName(a)[0];else{c=document;var
					d=b||c;a=d.querySelectorAll&&d.querySelector&&a?d.querySelector(a?"."+a:""):_.we(c,a,b)[0]||null}return
					a||null}; _.we=function(a,b,c){var d;a=c||a;if(a.querySelectorAll&&a.querySelector&&b)return
					a.querySelectorAll(b?"."+b:"");if(b&&a.getElementsByClassName){var e=a.getElementsByClassName(b);return
					e}e=a.getElementsByTagName("*");if(b){var f={};for(c=d=0;a=e[c];c++){var g=a.className;typeof
					g.split=="function"&&_.ta(g.split(/\s+/),b)&&(f[d++]=a)}f.length=d;return f}return
					e};_.ye=function(a){return _.xe(document,a)}; _.xe=function(a,b){b=String(b);a.contentType==="application/xhtml+xml"&&(b=b.toLowerCase());return
					a.createElement(b)};_.ze=function(a){for(var b;b=a.firstChild;)a.removeChild(b)};_.Ae=function(a){return
					a.nodeType==9?a:a.ownerDocument||a.document}; }catch(e){_._DumpException(e)}
					try{ _.Zi=function(a,b){let c,d;return(b=(d=(c=b.document).querySelector)==null?void
					0:d.call(c,`${a}[nonce]`))?b.nonce||b.getAttribute("nonce")||"":""};_.$i=function(a){const
					b=_.Zi("script",a.ownerDocument&&a.ownerDocument.defaultView||window);b&&a.setAttribute("nonce",b)};_.aj=function(a){if(!a)return
					null;a=_.J(a,4);var b;a===null||a===void 0?b=null:b=_.ie(a);return b};_.bj=class
					extends _.Q{constructor(a){super(a)}};_.cj=function(a,b){return(b||document).getElementsByTagName(String(a))};
					}catch(e){_._DumpException(e)} try{ var ej=function(a,b,c){a
					<b?dj(a+1,b):_.Zc.log(Error(
					"ca`"+a+ "`"+b),{url:c})},dj=function(a,b){if(fj){const c=_.ye( "SCRIPT");c.async=!0;c.type="text/javascript"
					;c.charset="UTF-8" ;c.src=_.ge(fj);_.$i(c);c.onerror=_.Wd(ej,a,b,c.src);_.cj(
					"HEAD")[0].appendChild(c)}},gj=class extends _.Q{constructor(a){super(a)}};var hj=_.F(_.kd,gj,17)||new
					gj,ij,fj=(ij=_.F(hj,_.bj,1))?_.aj(ij):null,jj,kj=(jj=_.F(hj,_.bj,2))?_.aj(jj):null,lj=function(){dj(1,2);if(kj){const
					a=_.ye( "LINK");a.setAttribute( "type", "text/css");a.href=_.ge(kj).toString();a.rel="stylesheet"
					;let b=_.Zi( "style",window);b&&a.setAttribute( "nonce",b);_.cj( "HEAD")[0].appendChild(a)}};(function(){const
					a=_.ld();if(_.I(a,18))lj();else{const b=_.Yd(a,19)||0;window.addEventListener(
					"load",()=>{window.setTimeout(lj,b)})}})(); }catch(e){_._DumpException(e)} })(this.gbar_);
						// Google Inc.
						</script>
						<div>
							<div></div>
						</div>
	</div>
	<textarea class="csi" name="csi" style="display:none"></textarea>
	<div class="gb_n" ng-non-bindable="">Google アプリ</div>
	<script nonce="">
	(function() {
		google.caft = function(a) {
			if (google.aftq === null) try {
				a()
			} catch (b) {
				google.ml(b, !1)
			} else google.aftq = google.aftq || [], google.aftq.push(a)
		};
		window.google = window.google || {};
		google.c.iim = google.c.iim || {};
		(function() {
			var a = Date.now();
			google.tick("load", "prt", a);
			performance && performance.mark && performance.mark("SearchBodyEnd");
			google.c.e("load", "imn", String(document.getElementsByTagName("img").length));
			google.c.ub();
			google.c.cae || google.c.maft(a, null);
			google.c.miml(a);
			google.rll(window, !1, function() {
				google.tick("load", "old")
			});
			google.c.u("prt")
		})();
	}).call(this);
	(function() {
		window.google = window.google || {};
		window.google.ishk = [];

		function a() {
			return window.scrollY + window.document.documentElement.clientHeight >=
				Math.max(document.body.scrollHeight, document.body.offsetHeight)
		}

		function b() {
			a() && window.google.ishk.length === 0 && (window.google.bs = !0, window.removeEventListener(
				"scroll", b))
		}
		a() ? window.google.bs = !0 : (window.google.bs = !1, window.addEventListener(
			"scroll", b));
	}).call(this);
	(function() {
		google.jl = {
			bfl: 0,
			dw: false,
			ine: false,
			ubm: false,
			uwp: true,
			vs: false
		};
	})();
	(function() {
		var pmc =
			'{\"aa\":{},\"abd\":{\"abd\":false,\"deb\":false,\"det\":false},\"async\":{},\"cdos\":{\"cdobsel\":false},\"cr\":{\"qir\":false,\"rctj\":true,\"ref\":false,\"uff\":false},\"csi\":{},\"d\":{},\"gf\":{\"pid\":196},\"hsm\":{},\"ifl\":{\"lsf_is_launched\":true,\"opts\":[{\"href\":\"/search?q=%E5%A4%95%E9%A3%9F%E3%81%AE%E3%83%AC%E3%82%B7%E3%83%94\",\"id\":\"hungry\",\"msg\":\"\\u304a\\u8179\\u304c\\u3059\\u3044\\u305f\"},{\"href\":\"/search?q=%E3%82%B3%E3%82%A4%E3%83%B3%E3%83%88%E3%82%B9\\u0026csf=b\",\"id\":\"adventurous\",\"msg\":\"\\u5192\\u967a\\u3057\\u305f\\u3044\"},{\"href\":\"/url?url=https://google.com/doodles/30th-anniversary-of-pac-man\\u0026sa=t\\u0026usg=AOvVaw2wX4wyfipP8URIIlObmLNl\",\"id\":\"playful\",\"msg\":\"\\u904a\\u3073\\u305f\\u3044\\u6c17\\u5206\"},{\"href\":\"/url?url=https://www.google.co.jp/search?q%3D%25E3%2582%25AA%25E3%2583%25AA%25E3%2582%25AA%25E3%2583%25B3%25E6%2598%259F%25E9%259B%25B2%26um%3D1%26ie%3DUTF-8%26tbm%3Disch%26csf%3Db\",\"id\":\"stellar\",\"msg\":\"\\u661f\\u306b\\u306a\\u3063\\u305f\\u6c17\\u5206\"},{\"href\":\"/url?url=/doodles\",\"id\":\"doodley\",\"msg\":\"Doodle \\u3092\\u63a2\\u305d\\u3046\"},{\"href\":\"/url?url=https://trends.google.com/trends/trendingsearches/daily?geo%3DJP\\u0026sa=t\\u0026usg=AOvVaw1hB2c9TS_NlCP6i3PBQwSv\",\"id\":\"trendy\",\"msg\":\"\\u30c8\\u30ec\\u30f3\\u30c7\\u30a3\\u30fc\\u306a\\u6c17\\u5206\"},{\"href\":\"/url?url=https://artsandculture.google.com/asset/egH2dNwwMCPBnQ?hl%3Dja%26gl%3Djp\\u0026sa=t\\u0026usg=AOvVaw0DzkpxTWywcSqOYliGFUG2\",\"id\":\"artistic\",\"msg\":\"\\u82b8\\u8853\\u5bb6\\u6c17\\u5206\"},{\"href\":\"/url?url=https://www.google.co.jp/search?q%3D%25E9%259D%25A2%25E7%2599%25BD%25E3%2581%2584%25E7%258C%25AB%25E3%2581%25AE%25E3%2583%259F%25E3%2583%25BC%25E3%2583%25A0%26um%3D1%26ie%3DUTF-8%26tbm%3Disch%26csf%3Db\",\"id\":\"funny\",\"msg\":\"\\u7b11\\u3044\\u305f\\u3044\\u6c17\\u5206\"}]},\"jsa\":{\"csi\":true,\"csir\":100},\"mb4ZUb\":{},\"pHXghd\":{},\"sb_wiz\":{\"rfs\":[],\"scq\":\"\",\"stok\":\"nq58laltQa1697xytbNOKS8-aj4\"},\"sf\":{},\"sonic\":{},\"spch\":{\"ae\":\"\\u30de\\u30a4\\u30af\\u3092\\u78ba\\u8a8d\\u3057\\u3066\\u304f\\u3060\\u3055\\u3044\\u3002\\u003Ca href=\\\"https://support.google.com/chrome/?p=ui_voice_search\\\" target=\\\"_blank\\\"\\u003E\\u8a73\\u7d30\\u003C/a\\u003E\",\"ak\":\"\",\"ao\":true,\"cd\":0,\"fp\":true,\"hl\":\"ja-JP\",\"im\":\"\\u97f3\\u58f0\\u691c\\u7d22\\u3092\\u958b\\u59cb\\u3059\\u308b\\u306b\\u306f [\\u003Cb\\u003E\\u8a31\\u53ef\\u003C/b\\u003E] \\u3092\\u30af\\u30ea\\u30c3\\u30af\\u3057\\u3066\\u304f\\u3060\\u3055\\u3044\",\"iw\":\"\\u5f85\\u6a5f\\u3057\\u3066\\u3044\\u307e\\u3059...\",\"lm\":\"\\u304a\\u8a71\\u3057\\u304f\\u3060\\u3055\\u3044...\",\"lu\":\"%1$s\\u306e\\u97f3\\u58f0\\u691c\\u7d22\\u306f\\u3054\\u5229\\u7528\\u306b\\u306a\\u308c\\u307e\\u305b\\u3093\",\"mb\":false,\"mc\":false,\"ne\":\"\\u30a4\\u30f3\\u30bf\\u30fc\\u30cd\\u30c3\\u30c8\\u306b\\u63a5\\u7d9a\\u3055\\u308c\\u3066\\u3044\\u307e\\u305b\\u3093\",\"nt\":\"\\u805e\\u304d\\u53d6\\u308c\\u307e\\u305b\\u3093\\u3067\\u3057\\u305f\\u3002\\u003Cspan\\u003E\\u3082\\u3046\\u4e00\\u5ea6\\u304a\\u8a66\\u3057\\u304f\\u3060\\u3055\\u3044\\u003C/span\\u003E\",\"nv\":\"\\u30de\\u30a4\\u30af\\u3068\\u97f3\\u58f0\\u306e\\u30ec\\u30d9\\u30eb\\u3092\\u78ba\\u8a8d\\u3057\\u3066\\u304f\\u3060\\u3055\\u3044\\u3002\\u003Ca href=\\\"https://support.google.com/chrome/?p=ui_voice_search\\\" target=\\\"_blank\\\"\\u003E\\u8a73\\u7d30\\u003C/a\\u003E\",\"pe\":\"\\u97f3\\u58f0\\u691c\\u7d22\\u306f\\u30aa\\u30d5\\u306b\\u306a\\u3063\\u3066\\u3044\\u307e\\u3059\\u3002\\u003Ca href=\\\"https://support.google.com/chrome/?p=ui_voice_search\\\" target=\\\"_blank\\\"\\u003E\\u8a73\\u7d30\\u003C/a\\u003E\",\"ri\":false,\"rm\":\"\\u304a\\u8a71\\u3057\\u304f\\u3060\\u3055\\u3044\",\"s3\":false,\"sa\":false}}';
		google.pmc = JSON.parse(pmc);
	})();
	(function() {
		var r = ['sb_wiz', 'aa', 'abd', 'async', 'ifl', 'pHXghd', 'sf', 'sonic',
			'spch'
		];
		google.plm(r);
	})();
	(function() {
		var m = {
			"B1Nv6k": ["gws-wiz", "", "", "", null, 1, 0, 0, 13, "ja", null, "",
				"KnDAZtO4CObk2roP-pvLiAs", 0, "ja", null, null, null, 3, 5, -1, null,
				"89978449", null, 1, 0, 1800000, 1, 6, null, 1.15, 1, 1, 0, null, 1, 1,
				0, null, null, null, null, 1, 1, null, "", 0, 1, null, null, null, 0, 0,
				0, "futura_sug_zp_si_0000000_e", null, null, "", 0, null, 1, -1, -1,
				null, 1, 0, 1, 1000, 1, ["gws-wiz", "", ""], null, [
					"gws-wiz-modeless-local", "", ""
				], null, ["img", "gws-wiz-img", "i"], null, ["gws-wiz-modeless-products",
					"", "sh"
				], null, ["gws-wiz-modeless", "gws-wiz-perspectives", ""], null, [
					"gws-wiz-modeless-lodging", "", ""
				], null, ["gws-wiz-modeless-flights", "", ""], 1, null, 0, 1, null, null,
				null, ["gws-wiz-modeless-vss-products", "", ""], null, [
					"gws-wiz-modeless-vss-jobs", "", ""
				], null, ["gws-wiz-modeless-vss-local-travel", "", ""], 1, null, null, [
					"gws-wiz-modeless-video", "", "v"
				], null, null, null, ["gws-wiz-modeless-jobs", "", ""], null, [
					"gws-wiz-modeless-vss-flights", "", ""
				], null, ["gws-wiz-modeless", "", ""], null, null, null, [
					"gws-wiz-modeless-shopping", "", "sh"
				], null, null, null, 0, ["multimodal-lens-web", "", ""],
				["gws-wiz-modeless", "", ""], 0
			],
			"B1Nv6o": [null, null, null, "autocomplete_user_feedback_kp_id", null, 11,
				null, null, null, null, null, 5010715, "searchbox", null,
				"AutocompletePrediction", null, null, null, null, 11
			],
			"B1Nv6s": [3, 6, null, null, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0],
			"B1Nv6w": ["", 6, 0],
			"B1Nv60": ["", 4, 0]
		};
		var a = m;
		if (window.W_jd)
			for (var b in a) window.W_jd[b] = a[b];
		else window.W_jd = a;
	})();
	(function() {
		window.WIZ_global_data = {
			"w2btAe": "%.@.\"\",\"\",\"0\",null,null,null,1]",
			"STfaRd": "{}",
			"oxN3nb": {
				"1": false
			},
			"Im6cmf": "/wizrpcui/_/WizRpcUi",
			"QrtxK": "0",
			"LVIXXb": "1",
			"SNlM0e": "",
			"S06Grb": "",
			"eptZe": "/wizrpcui/_/WizRpcUi/",
			"Yllh3e": "%.@.1723887658138323,22458982,2970799610]",
			"GWsdKe": "ja-JP",
			"zChJod": "%.@.null,\"https://www.google.co.jp/log?format\\u003djson\"]",
			"S6lZl": "89978449"
		};
		window.IJ_values = {
			"eG8Zqf": 1.0,
			"IvNqzc": false,
			"qjWw6c": true,
			"GbxFme": true,
			"oI8LH": false,
			"IXFWPb": false,
			"vSjUZd": 24,
			"P59QTc": false,
			"gfq1Ic": false,
			"HKzGBb": false,
			"B4LUOc": false,
			"q9jm5e": false,
			"zIfn3e": false,
			"bs2drc": false,
			"hnypGb": false,
			"yys2yc": false,
			"Rbaz9c": false,
			"SoPmHd": false,
			"lCCykc": false,
			"ro3IRe": false,
			"eflcTd": false,
			"NdHRde": false,
			"MlUHWc": false,
			"CzxWj": false,
			"kyqNwe": false,
			"ucii4d": false,
			"GL2pid": false,
			"QRQY4b": false,
			"vwAn2d": false,
			"WdWVbc": false,
			"Tv95nc": false,
			"urls1d": false,
			"mhcbZb": false,
			"ogmk0d": false,
			"RK9az": false,
			"T62UHb": false,
			"jCekpb": false,
			"cTU58": false,
			"kRerQb": false,
			"oS0end": false,
			"AoIPu": true,
			"CieUQe": true,
			"HCMJkf": true,
			"zNiNDd": false,
			"EsWLY": false,
			"XP4Noc": false,
			"jqcxU": "#4285f4",
			"toVELc": "#f8f9fa",
			"V1TJEb": "#1a73e8",
			"eavN9c": 36,
			"XuC5Td": 24,
			"ivyWed": 28,
			"psmQyf": 6,
			"hOkjMc": 0,
			"qOpwJd": -1,
			"UlHllb": 1.0,
			"osNyZ": 1.0,
			"L6WyEf": false,
			"tswRXd": "none",
			"vq4Rhf": true,
			"mtmrtb": "0 1px 6px rgba(32,33,36,0.28)",
			"hOdcKb": false,
			"Kw419e": false,
			"U2GTk": "#fff",
			"WgRLme": "#dadce0",
			"QcZxSd": "#3c4043",
			"g4ToDf": "0 1px 2px rgba(60,64,67,.3), 0 2px 6px 2px rgba(60,64,67,.15)",
			"AsC4Mb": "#9aa0a6",
			"mub7Fd": "#f1f3f4",
			"z2SQwf": "#bdc1c6",
			"ob4Y0c": "#e8eaed",
			"M1fk3b": "#dadce0",
			"gWINCf": "#9aa0a6",
			"I6R5lf": "#f8f9fa",
			"KCMXVb": "#202124",
			"vzRvgb": "#e8f0fe",
			"HNLwz": "#d2e3fc",
			"uD3Lwc": "#d2e3fc",
			"TqDTGf": "#aecbfa",
			"m7EnTc": "#8ab4f8",
			"jyEUXe": "#d2e3fc",
			"QyzZ8e": "#174ea6",
			"CFgsb": "#1558d6",
			"m0RlKb": false,
			"wFGKdc": false,
			"klgere": "invert(1) hue-rotate(180deg)",
			"gHo7b": "#b8bbbe",
			"VBSc8c": false,
			"oX2r2c": false,
			"WitVqe": false,
			"JuXRyb": false,
			"zsYZK": "#dadce0",
			"Pi4f8d": false,
			"nNHNPc": false,
			"VD4u1d": false,
			"xxthqf": true,
			"XIHhCb": true,
			"UsVc8e": false,
			"HIMA4e": false,
			"YjL9Ce": false,
			"wsRfI": false,
			"UZoA2e": false,
			"q49bvd": false,
			"m2hzy": false,
			"fTZUNc": false,
			"YrTYaf": true,
			"WvdhF": false,
			"Rojixc": "#aecbfa",
			"QOuvIc": "#1a73e8",
			"hhsybf": false,
			"Zxl9ce": false,
			"OL2x3c": false,
			"Zun3Ef": false,
			"SOm4o": false,
			"lL47Xc": false,
			"l4Npee": false,
			"tyCgpc": "#fff",
			"H7aRye": "0px 5px 26px 0px rgba(0, 0, 0, 0.22), 0px 20px 28px 0px rgba(0, 0, 0, 0.30)",
			"U6xP0": "#4285f4",
			"A5tF3b": false,
			"j0DpSe": false,
			"NXDvtf": false,
			"Lxmjn": false,
			"FydCC": false,
			"ywhzh": false,
			"EgTnfe": true,
			"kAUP3b": false,
			"hgWJ8c": false,
			"TxsTcf": "#000",
			"v4iQCe": "#4285f4",
			"OfqeOe": "#4285f4",
			"zRpUk": "#4285f4",
			"QbZklb": "#e8f0fe",
			"Fcb4A": "#1a73e8",
			"VRtZRe": "#1558d6",
			"OmYlge": "#34a853",
			"y8HGgf": "#1e8e3e",
			"QDXUyc": "#188038",
			"JQWqub": "#ea4335",
			"nRwuZd": "#d93025",
			"rzzybc": "#d93025",
			"rZLJJb": "#fff",
			"hcLEtc": "#81c995",
			"GJQmmf": "#34a853",
			"hETIfb": "#dadce0",
			"NtNjtd": "#dadce0",
			"vCsrw": "#dadce0",
			"p9416c": "#f8f9fa",
			"toQ7tf": "#f8f9fa",
			"xgY1nc": "#f8f9fa",
			"p1ocJb": "#f8f9fa",
			"FCLfBe": "#f8f9fa",
			"MnC2zf": "#70757a",
			"IfdAAd": "#70757a",
			"fP2Yo": "#70757a",
			"mknyu": "#70757a",
			"PUenT": "#3c4043",
			"Z0DEKf": "#202124",
			"oHHKwf": "#202124",
			"xNPzic": "#fff",
			"KkPbyc": "#fbbc04",
			"uezre": "#fbbc04",
			"SkGiZd": "#f29900",
			"OxPRr": "#f1f3f4",
			"uiKEV": "#202124",
			"bhxjsd": false,
			"Co7tHc": true,
			"qcvoqe": false,
			"BPltf": "#f1f3f4",
			"kcrUme": 14,
			"m8l8td": "CARET",
			"zHsZtb": "#3c4043",
			"zeWvtf": false,
			"qdoinb": "#70757a",
			"a4qLne": "#ea4335",
			"RifN2d": "#000",
			"Fpi7Rc": "Arial,sans-serif-medium,sans-serif",
			"a2ykac": "Arial,sans-serif",
			"ME4NMc": "#000",
			"BpPAcd": "#dadce0",
			"N0wyZ": "#000",
			"jxZxne": "#70757a",
			"CQvMbe": "#1a73e8",
			"fRkoq": true,
			"c4qycc": false,
			"N98mef": false,
			"WkjuOe": false,
			"mIjP6d": false,
			"uJ8Xid": false,
			"cWwp7b": false,
			"h6eQZc": false,
			"b0Jode": false,
			"mo8CW": true,
			"CAM7Vc": false,
			"MomrM": false,
			"Vb9YJ": true,
			"OQZvxe": "0 2px 10px 0 rgba(0,0,0,0.2)",
			"fI0P7e": false,
			"Asoj0e": false,
			"JcUGee": "#70757a",
			"PngPbb": "#202124",
			"ENmP1c": "rgba(204,204,204,.15)",
			"I69zkb": "rgba(204,204,204,.25)",
			"a8Umdd": "rgba(112,117,122,.40)",
			"seVajd": "rgba(0,0,0,.12)",
			"esUgv": "#fff",
			"KVmtZc": "rgba(255,255,255,.30)",
			"MoAfyf": "#fff",
			"ALMSwe": "Roboto,RobotoDraft,Helvetica,Arial,sans-serif",
			"Sgnmlc": "14px",
			"qkXvHd": "500",
			"SezQgf": "500",
			"EJG4vf": "pointer",
			"WyvaRd": "0 1px 1px rgba(0,0,0,.16)",
			"ROAn0e": "0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12)",
			"rgHLF": true,
			"KzjxBb": false,
			"NQ4wzb": false,
			"TLsp9d": false,
			"S3hspc": true,
			"Tae7A": true,
			"c5h25": true,
			"MCowFd": false,
			"LACYrf": false,
			"uZLNF": true,
			"wku5sd": false,
			"JdPOaf": false,
			"zBxT5": false,
			"bDOvJc": false,
			"ZMIIMe": true,
			"B0husb": true,
			"o28sBd": false,
			"n4eEIc": true,
			"tqmosb": "#fff",
			"HjM8R": "#fff",
			"FqP1Fc": "#000",
			"SATNMc": "1px solid #dadce0",
			"V0Bluc": "none",
			"X1bUEc": "Arial,sans-serif-medium,sans-serif",
			"QZheGe": "Arial,sans-serif-medium,sans-serif",
			"LIYDac": "Arial,sans-serif",
			"mNmrAb": "#ebebeb",
			"x0VCkc": "1px solid #dadce0",
			"Rvxsx": "1px solid #dadce0",
			"qmcJmd": 6,
			"JuqxTb": "#202124",
			"E6Gkjd": "0 2px 10px 0 rgba(0,0,0,0.2)",
			"MClBOe": "rgba(0,0,0,0.1)",
			"V6eh7c": 16,
			"ZxI7Af": "#fafafa",
			"sKPNrc": "#e6e6e6",
			"AgJzQ": "#dadce0",
			"FagChc": "#fff",
			"tCGJz": "#fafafa",
			"oqx7yb": "#70757a",
			"khoEPb": "#1a0dab",
			"SfSmD": "#dadce0",
			"auaxA": "#202124",
			"qtDmFc": "#dadce0",
			"v44rSc": "#70757a",
			"YkyDVb": false,
			"s6k9tc": true,
			"tdC6kd": true,
			"avBLic": false,
			"UjGOq": false,
			"pWkoAb": false,
			"IUj4Ye": false,
			"KYi16e": false,
			"kBxgab": false,
			"lHLMtb": false,
			"Erzlz": false,
			"KQw3Q": false,
			"OQFPef": false,
			"m19P4e": false,
			"P6Ur2b": "#1a73e8",
			"uhXPIc": "#8ab4f8",
			"e127Sb": "#1c3aa9",
			"ezFdNd": "#0f9d58",
			"Wja4f": "#87ceac",
			"jjajId": "#9e9e9e",
			"d1ULv": "rgba(0,0,0,.26)",
			"lQ1kYd": "#bdbdbd",
			"fAus6": "#000",
			"NNBneb": "#5f6368",
			"MDi8Rd": "#dadce0",
			"BoJtxf": false,
			"ZTuJNc": false,
			"So4wae": false,
			"XgWQKd": true,
			"fjc61": false,
			"y1HZEd": false,
			"zAKfhf": false,
			"D8A8he": true,
			"bmQ7Rb": false,
			"nMRhJe": false,
			"xT28q": false,
			"KTkDB": false,
			"JyBo2c": false,
			"xDKXr": false,
			"FYBlgf": false,
			"FELoce": false,
			"HpkQdc": true,
			"FuMeW": true,
			"bcz7kc": false,
			"hVG5ce": false,
			"KCmv6e": false,
			"IAtx5d": true,
			"PIZdId": true,
			"VXIo7d": "8px",
			"EiEfXb": "#dadce0",
			"IFkMhd": false,
			"lsK6rd": true,
			"zhkRO": "%.@.0,0,0,0,1,0,0,0,null,1,null,0,0,null,0,1,0,\"/setprefs?sig\\u003d0_6BMaq_zTvg8uMrbscQz5E-PW-Kw%3D\\u0026szl\\u003d0\"]",
			"w2btAe": "%.@.\"\",\"\",\"0\",null,null,null,1]",
			"pxO4Zd": "0",
			"mXOY5d": "%.@.null,1,1,null,[null,757,1440]]",
			"SsQ4x": "HFJNGmmrQtv0T52ih3TK4A",
			"IYFWl": "%.@.\"#b8bbbe\"]",
			"Ht1O2b": "%.@.0]",
			"d6J1ld": "%.@.0]",
			"Oo3dKf": "%.@.\"0px 5px 26px 0px rgba(0,0,0,0.22),0px 20px 28px 0px rgba(0,0,0,0.3)\",\"#fff\"]",
			"uUBnEb": "",
			"nfxEDe": "%.@.[],0,null,0,0]",
			"auIt8": "%.@.0,0]",
			"YPqjbf": "%.@.\"rgba(0,0,0,0.9)\",\"#fff\",\"0 0 2px 0 rgba(0,0,0,0.12),0 2px 2px 0 rgba(0,0,0,0.12)\",\"1px solid #dadce0\",\"#70757a\"]",
			"MuJWjd": false,
			"GWsdKe": "ja-JP",
			"frJqAd": "%.@.\"13px\",\"16px\",\"11px\",13,16,11,\"8px\",8,20]",
			"N1ycab": "ja_JP",
			"AB5Xwb": "%.@.\"10px\",10,\"16px\",16,\"18px\"]",
			"Z8HLFf": "%.@.\"14px\",14]",
			"ymaOI": "%.@.40,32,14,\"\\\"#3c4043\\\"\"]",
			"fNpQmb": "",
			"aMI2mb": "%.@.\"0 2px 10px 0 rgba(0,0,0,0.2)\"]",
			"BZUDzc": "%.@.0,\"14px\",\"500\",\"500\",\"0 1px 1px rgba(0,0,0,.16)\",\"pointer\",\"#000\",null,\"#70757a\",\"#202124\",\"rgba(204,204,204,.15)\",\"rgba(204,204,204,.25)\",null,\"rgba(112,117,122,.40)\",\"#34a853\",\"#4285f4\",\"#1558d6\",\"#ea4335\",\"#fbbc04\",\"#f8f9fa\",\"#f8f9fa\",\"#202124\",\"#34a853\",\"rgba(0,0,0,.12)\",null,\"#fff\",\"rgba(255,255,255,.30)\",\"#fff\",\"#202124\",\"#fff\",null,0]",
			"v7Qvdc": "%.@.\"20px\",\"500\",\"400\",\"13px\",\"15px\",\"15px\",\"Roboto,RobotoDraft,Helvetica,Arial,sans-serif\",\"24px\",\"400\",\"32px\",\"24px\"]",
			"MgUcDb": "JP",
			"SIsrTd": false,
			"fyLpDc": "",
			"JPnTp": "%.@.\"#f1f3f4\",\"36px\"]",
			"ZxtPCd": "%.@.{\"100\":\"12px\",\"101\":\"8px\",\"102\":\"8px\",\"103\":\"10px\",\"104\":\"9px\"}]",
			"DwYRY": "%.@.\"#1967d2\",\"32px\",\"1px\",\"2px\",\"var(--bbQxAb)\",\"var(--mXZkqc)\",\"transparent\",\"transparent\",\"#1967d2\",\"#d2d2d261\",\"#47474761\",\"#1f1f1f33\",\"#1f1f1f33\",\"#1f1f1f66\",\"#0b57d015\",\"#0b57d015\",\"#0b57d039\",\"#0b57d015\",\"#0b57d015\",\"#0b57d039\",\"#0b57d015\",\"#0b57d015\",\"#0b57d039\",\"#001d3533\",\"#001d3539\",\"#001d3566\",\"rgba(31,31,31,0.08)\",\"rgba(31,31,31,0.078431375)\",\"rgba(31,31,31,0.23921569)\"]",
			"NyzCwe": "%.@.null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,\"18px\",\"20px\",\"18px\",\"#202124\",\"16px\",\"var(--IXoxUe)\",\"var(--YLNNHc)\"]",
			"spz2q": "%.@.\"var(--xhUGwc)\",null,null,null,null,\"0px\"]",
			"geiQxc": "%.@.\"234px\",\"176px\",\"204px\",\"172px\",\"128px\",\"148px\",\"111px\",\"83px\",\"92px\"]",
			"xFmcof": "%.@.null,null,null,\"20px\",null,\"12px\"]",
			"lDqiof": "%.@.\"var(--YLNNHc)\",\"var(--bbQxAb)\",\"var(--rrJJUc)\",null,\"var(--IXoxUe)\",\"var(--JKqx2)\",\"#681da8\",null,null,\"var(--xhUGwc)\",\"var(--Nsm0ce)\",\"var(--EpFNW)\",\"#e8f0fe\",\"#001d35\",\"#f1f3f4\",\"#1f1f1f\",\"#fff\",\"#1f1f1f\",\"#1f1f1f\",\"#fff\",\"#fff\",\"#fff\",\"#146c2e\",\"#b3261e\",\"#b06000\",\"var(--mXZkqc)\",\"#fff\",\"rgba(0,0,0,0.6)\",\"var(--COEmY)\",\"var(--gS5jXb)\",\"#d2e3fc\",null,\"var(--TMYS9)\",\"#5e5e5e\",null,\"transparent\",\"#dadce0\",\"rgba(0,0,0,0.03)\",null,null,null,null,null,null,null,null,null,\"#ea4335\",\"#34a853\",\"#4285f4\",\"#fbbc04\",\"#fbbc04\",\"#dadce0\",\"#f3f5f6\",null,null,null,null,\"#e8f0fe\",\"var(--XKMDxc)\",\"var(--aYn2S)\",null,\"var(--Aqn7xd)\",null,\"#b3261e\",\"#f9dedc\",\"#ffdf92\",\"#f4bf00\",\"#fff\",\"#410e0b\",\"#241a00\",\"#241a00\",\"#fff\",\"#072711\",\"#b3261e\",\"#146c2e\",\"#146c2e\",\"#c4eed0\",\"var(--nwXobb)\",\"var(--vZe0jb)\",\"var(--QWaaaf)\",\"var(--ZEpPmd)\",\"#a9acaa\",\"var(--Lm570b)\",\"#fff\",\"var(--jINu6c)\",\"var(--BRLwE)\",\"var(--DEeStf)\",\"var(--TSWZIb)\",\"var(--uLz37c)\",null,\"#545d7e\",\"var(--TyVYld)\",null,null,null,null,\"var(--VuZXBd)\",\"rgba(23,23,23,0.75)\",{\"100\":\"rgba(248,249,250,0.96)\",\"101\":\"rgba(255,255,255,0.8)\",\"102\":\"rgba(60,64,67,0.16)\",\"103\":\"#1967d2\",\"104\":\"#202124\",\"105\":\"#f1f3f4\"}]",
			"Gpnz4c": "%.@.\"#e0e9ff\",\"#dadce0\",\"#d2d2d2\",\"#0b57d0\",\"#747878\",\"#001d35\",null,\"#ebf1ff\",\"#001d35\",\"#d3e3fd\",\"#fff\",\"#5e5e5e\",\"#474747\",\"#1f1f1f\",\"#1a0dab\",\"#d2d2d2\",null,\"#0b57d0\",\"#a3c9ff\",\"#001d35\",\"#ecedee\",\"#f7f8f9\",\"#fff\",null,\"#f7f8f9\",\"#e0e9ff\",\"#f5f8ff\",\"#d3e3ff\",\"#a3c9ff\",null,\"#f5f8ff\",\"#0b57d0\",\"#545d7e\",\"#001d35\",null,\"#ebf1ff\",\"#001d35\",\"#c7dbff\",\"#fff\",\"#fff\",\"#545d7e\",\"#001d35\",\"#001d35\",\"#0b57d0\",\"#a3c9ff\",\"#0b57d0\",null,\"rgba(0,0,0,0.6)\",\"#a3c5ff\",\"#001d35\",\"#fff\",\"#f5f8ff\",\"#e5edff\",\"#ecedee\",\"#446eff\",\"#b1c5ff\",\"#c8ecff\"]",
			"kXVUzd": "%.@.\"40px\",\"48px\"]",
			"DT34Qc": "%.@.\"44px\",\"rgba(26,115,232,0.08)\",\"36px\",\"#f1f3f4\",20,18,16,\"#202124\"]",
			"sCU50d": "%.@.null,\"none\",null,\"0px 1px 3px rgba(60,64,67,0.08)\",null,\"0px 2px 6px rgba(60,64,67,0.16)\",null,\"0px 4px 12px rgba(60,64,67,0.24)\",null,null,\"1px solid var(--mXZkqc)\",\"0\",\"0\",\"0\",null,\"0px 1px 3px rgba(60,64,67,0.24)\",\"0\"]",
			"w9Zicc": "%.@.\"#f1f3f4\",\"26px\",\"#e2eeff\",\"#0060f0\",\"#e2eeff\",\"1px\",\"#dadce0\",\"1px\",\"#fff\",\"#dadce0\",null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,\"28px\",\"10px\",\"8px\",\"20px\",\"10px\",\"var(--XKMDxc)\",\"var(--mXZkqc)\",\"#fff\",\"var(--TSWZIb)\",\"var(--TMYS9)\",\"var(--TSWZIb)\",\"var(--TMYS9)\"]",
			"IkSsrf": "%.@.\"Arial,sans-serif\",\"Arial,sans-serif-medium,sans-serif\",\"Arial,sans-serif\",\"Arial,sans-serif-medium,sans-serif\",\"Arial,sans-serif-light,sans-serif\"]",
			"MR0w4": "%.@.\"var(--google-fs,1)\",\"var(--google-screen-scale-ratio,1)\"]",
			"OItNqf": "%.@.null,\"24px\"]",
			"JMyuH": "%.@.]",
			"j2FoS": "%.@.null,null,null,null,null,null,null,null,\"20px\"]",
			"e2zoW": "%.@.\"16px\",\"12px\",\"0px\",\"8px\",\"4px\",\"2px\",\"20px\",\"24px\",\"48px\",\"20px\",null,null,\"0px\",\"20px\",\"36px\",\"20px\",null,\"83px\",\"52px\",\"6px\",\"20px\",\"18px\",\"16px\",\"24px\",\"12px\",\"6px\",\"75px\",\"52px\",\"940.98px\",\"684px\",\"683.98px\",\"1163.98px\",\"941px\",\"1560px\",\"1164px\"]",
			"W1Bte": "%.@.\"cubic-bezier(0.1,1,0.2,1)\",\"cubic-bezier(0.8,0,1,0.8)\",\"cubic-bezier(0.2,0.6,0.2,1)\",\"cubic-bezier(0.4,0,1,0.8)\",\"300ms\",\"100ms\",\"200ms\",\"250ms\",\"cubic-bezier(0.4,0,0.2,1)\",\"cubic-bezier(0.4,0,0.6,1)\",\"cubic-bezier(0.6,0,0,1)\",\"cubic-bezier(0,0,1,1)\",\"cubic-bezier(0.2,0,0,1)\",\"800ms\",\"1000ms\",\"400ms\",\"500ms\",\"600ms\",\"50ms\",\"400ms\",\"300ms\",\"250ms\",\"150ms\",\"250ms\",\"200ms\",\"150ms\",\"150ms\",\"300ms\",\"250ms\",\"200ms\",\"150ms\",\"450ms\",\"450ms\",\"300ms\",\"150ms\",\"300ms\",\"250ms\",\"200ms\",\"100ms\",\"250ms\",\"200ms\",\"150ms\",\"100ms\",\"250ms\",\"200ms\",\"150ms\",\"100ms\",\"300ms\",\"250ms\",\"200ms\",\"100ms\",\"null\",\"cubic-bezier(0.3,0,0.8,0.15)\",\"cubic-bezier(0.05,0.7,0.1,1)\",\"cubic-bezier(0,0,1,1)\",\"cubic-bezier(0.2,0,0,1)\",\"cubic-bezier(0.3,0,1,1)\",\"cubic-bezier(0,0,0,1)\",\"250ms\",\"200ms\",\"150ms\",\"50ms\",\"50ms\",\"50ms\",\"400ms\",\"350ms\",\"250ms\",\"50ms\",\"50ms\",\"50ms\",\"200ms\",\"150ms\",\"100ms\",\"50ms\",\"200ms\",\"150ms\",\"100ms\",\"50ms\",\"50ms\",\"50ms\",\"250ms\",\"200ms\",\"150ms\",\"50ms\",\"50ms\",\"50ms\",\"cubic-bezier(0.05,0.7,0.1,1)\",\"cubic-bezier(0.3,0,0.8,0.15)\"]",
			"pbvshf": "%.@.\"48px\"]",
			"u9mep": "%.@.\"#1a0dab\",null,\"#1f1f1f\",\"var(--JKqx2)\"]",
			"mrqaQb": "%.@.null,null,null,null,\"2px\",\"12px\"]",
			"k7Tqye": "%.@.null,null,null,null,null,null,null,\"16px\",\"12px\",\"8px\",\"20px\",\"4px\",\"9999px\",\"0px\",\"2px\"]",
			"y50LC": "%.@.null,null,\"#4d5156\",null,\"#5f6368\"]",
			"jfSEkd": "%.@.\"var(--Pa8Wlb)\",\"var(--KIZPne)\",\"var(--xPpiM)\",null,\"#d2e3fc\",\"#d2e3fc\",\"rgba(26,115,232,0.24)\",\"var(--pEa0Bc)\",\"var(--Yi4Nb)\",\"var(--kloG3)\",\"var(--YaIeMb)\",\"var(--izGsqb)\",\"var(--todMNcl)\",\"rgba(32,33,36,0.16)\",null,\"rgba(32,33,36,0.32)\",\"#ebf1ff\",\"#001d35\",\"rgba(32,33,36,0.08)\",\"rgba(32,33,36,0.08)\",\"rgba(32,33,36,0.24)\",\"transparent\",\"var(--rrJJUc)\",null,\"rgba(26,115,232,0.08)\",\"rgba(26,115,232,0.08)\",\"rgba(26,115,232,0.24)\",null,null,null,\"rgba(60,64,67,0.08)\",\"rgba(60,64,67,0.08)\",\"rgba(60,64,67,0.24)\",\"2px\",\"2px\",\"61\",\"var(--bbQxAb)\",\"#d3e3fd\",null,\"#0b57d0\",\"var(--XKMDxc)\",\"var(--YLNNHc)\",\"#5e5e5e\",\"var(--YLNNHc)\",\"var(--YLNNHc)\",\"15\",\"0.08\",\"39\",\"var(--jINu6c)\",\"rgba(32,33,36,0.16)\",\"33\",\"39\",\"var(--EpFNW)\",\"66\",\"#001d35\",\"#5e5e5e\",\"0.08\",\"var(--bbQxAb)\",\"0.08\",\"#5e5e5e\",\"var(--bbQxAb)\",\"0.24\",\"var(--IXoxUe)\",\"transparent\",\"0.08\",\"0.08\",\"var(--IXoxUe)\",\"0.24\",\"var(--IXoxUe)\",\"transparent\",\"0.08\",\"0.08\",\"var(--uLz37c)\",\"0.24\",\"var(--uLz37c)\",\"var(--jINu6c)\",\"var(--jINu6c)\",\"15\",\"#1967d2\",\"15\",\"#0b57d0\",\"39\",\"#0b57d0\",\"15\",\"15\",\"#0b57d0\",\"#001d35\",\"39\",\"var(--p9J9c)\",\"var(--jINu6c)\",\"15\",\"15\",\"39\",\"#0b57d0\",\"rgba(0,0,0,0.6)\",\"33\",\"33\",\"#fff\",\"66\",{\"100\":\"#fff\",\"101\":\"0.08\",\"102\":\"0.08\",\"103\":\"#1f1f1f\",\"104\":\"0.24\",\"105\":\"#1f1f1f\",\"106\":\"rgba(0,0,0,0.1)\",\"107\":\"0.08\",\"108\":\"#185abc\",\"109\":\"0.08\",\"110\":\"0.24\",\"111\":\"var(--Nsm0ce)\",\"112\":\"0\",\"113\":\"transparent\",\"114\":\"0.08\",\"115\":\"0.08\",\"116\":\"var(--YLNNHc)\",\"117\":\"0.24\",\"118\":\"var(--YLNNHc)\",\"119\":\"0.75\",\"120\":\"0.6\",\"121\":\"rgba(31,31,31,0.078431375)\",\"122\":\"rgba(31,31,31,0.08)\",\"123\":\"rgba(31,31,31,0.23921569)\",\"124\":\"rgba(11,87,208,0.078431375)\",\"125\":\"rgba(11,87,208,0.078431375)\",\"126\":\"rgba(11,87,208,0.23921569)\",\"127\":\"rgba(32,33,36,0.2)\",\"128\":\"rgba(32,33,36,0.2)\",\"129\":\"rgba(32,33,36,0.4)\",\"130\":\"rgba(32,33,36,0.078431375)\",\"131\":\"rgba(32,33,36,0.078431375)\",\"132\":\"rgba(32,33,36,0.23921569)\",\"133\":\"var(--Ehh4mf)\"}]",
			"GVtPm": "%.@.null,null,null,null,null,\"0 0 0 1px var(--mXZkqc)\",\"1px solid var(--mXZkqc)\",null,null,null,null,null,null,null,null,\"transparent\",\"rgba(23,23,23,0.3)\",null,null,\"16px\"]",
			"MexNte": "%.@.\"700\",\"400\",\"underline\",\"none\",\"capitalize\",\"none\",\"uppercase\",\"none\",\"500\",\"lowercase\",\"italic\",null,null,\"-1px\",\"0.3px\",\"20px\",\"12px\",null,\"12px\",\"14px\",\"16px\",\"18px\",\"22px\",\"24px\",\"26px\",\"28px\",\"32px\",\"36px\",\"40px\",\"48px\",\"52px\",\"56px\",\"60px\",\"14px\",\"16px\",\"18px\",\"20px\",\"22px\",\"24px\",\"28px\",\"36px\",\"40px\",\"45px\",\"48px\",\"56px\",\"0\",\"0.1px\"]",
			"Aahcnf": "%.@.\"28px\",\"36px\",\"400\",\"Arial,sans-serif\",null,\"Arial,sans-serif\",\"14px\",\"400\",\"22px\",null,\"18px\",\"24px\",\"400\",\"Arial,sans-serif\",null,\"Arial,sans-serif\",\"56px\",\"48px\",\"0\",null,\"400\",\"Arial,sans-serif\",\"36px\",\"400\",\"48px\",null,\"Arial,sans-serif\",\"36px\",\"28px\",null,\"400\",null,\"Arial,sans-serif\",\"24px\",\"18px\",null,\"400\",\"Arial,sans-serif\",\"16px\",\"12px\",null,\"400\",\"Arial,sans-serif\",\"24px\",\"16px\",null,\"400\",\"Arial,sans-serif\",\"24px\",\"20px\",null,\"400\",\"Arial,sans-serif\",\"24px\",\"16px\",null,\"400\",\"Arial,sans-serif\",\"18px\",\"14px\",null,\"400\",null,null,null,null,null,\"14px\",\"Arial,sans-serif\",\"20px\",\"400\",\"Arial,sans-serif\",\"28px\",\"22px\",\"400\",\"Arial,sans-serif\",\"24px\",\"16px\",\"400\",\"Arial,sans-serif-medium,sans-serif\",\"16px\",\"12px\",\"Arial,sans-serif\",\"28px\",\"22px\",\"400\",null,null,null,null,\"500\",\"0px\",\"0px\",\"0\"]",
			"PFhmed": "%.@.\"rgba(255,255,255,0)\",\"rgba(255,255,255,0.9)\",null,\"rgba(11,87,208,0.08)\",\"#f1f3f4\",\"rgba(32,33,36,0.5)\",\"#ecedee\",\"#ecedee\"]",
			"mf1yif": "%.@.4]",
			"B4pZbd": "JP",
			"aKXqGc": "%.@.\"14px\",14,\"16px\",16,\"0\",0,\"none\",632,\"1px solid #dadce0\",\"normal\",\"normal\",\"#70757a\",\"12px\",\"1.34\",\"1px solid #dadce0\",\"none\",\"0\",\"none\",\"none\",\"none\",\"none\",\"6px\",\"632px\"]",
			"ZP0oif": "%.@.\"16px\",\"#ebedef\"]",
			"o0P8Hf": "%.@.\"rgba(0,0,0,0.0)\",\"#fff\",\"rgba(255,255,255,.0)\",null,null,null,null,null,null,\"#f8f9fa\",\"#000\",\"#1a73e8\",\"#dadce0\",\"#fff\",\"#fff\",null,\"#70757a\",\"rgba(0,0,0,0.26)\",\"rgba(0,0,0,0.2)\",null,null,null,\"rgba(0,0,0,0.1)\",\"#fff\",null,null,\"#000\",null,null,null,\"rgba(255,255,255,0.5)\",null,\"rgba(0,0,0,0.3)\",\"rgba(0,0,0,0.2)\",null,null,\"rgba(0,0,0,.04)\",null,null,\"#70757a\",\"#70757a\",\"rgba(0,0,0,.22)\",\"rgba(0,0,0,.30)\",\"rgba(0,0,0,.06)\",null,\"#d2e3fc\",null,\"rgba(32,33,36,.7)\",null,null,null,\"rgba(255,255,255,.8)\",\"rgba(60,64,67,.15)\",null,\"rgba(0,0,0,.16)\",null,\"rgba(0,0,0,.14)\",\"rgba(0,0,0,.12)\",null,null,\"rgba(0,0,0,.24)\",\"rgba(0,0,0,.05)\",\"rgba(0,0,0,.13)\",\"rgba(60,64,67,.3)\",\"rgba(0,0,0,.36)\",\"rgba(0,0,0,.15)\",\"rgba(32,33,36,.28)\",\"rgba(218,220,224,.7)\",\"#dadce0\",\"#fff\",\"#fff\",\"#1a73e8\",\"#000\",\"rgba(0,0,0,.0)\",\"#202124\",\"rgba(0,0,0,.8)\",\"rgba(26,115,232,0)\",\"rgba(26,115,232,.7)\",null,\"rgba(32,33,36,.7)\",\"rgba(0,0,0,.8)\",null,null,null,null,\"rgba(255,255,255,.54)\",null,\"rgba(60,64,67,.38)\",\"rgba(255,255,255,.3)\",\"rgba(0,0,0,0.54)\",\"rgba(0,0,0,0.8)\",\"rgba(248,249,250,0.85)\",\"#dadce0\",\"#ea4335\",\"#34a853\",null,null,\"#3c4043\",\"#202124\",{\"100\":\"#f8f9fa\",\"101\":\"#dadce0\",\"102\":\"#3c4043\",\"106\":\"#70757a\",\"108\":\"#f8f9fa\",\"112\":\"#dadce0\",\"113\":\"#e8f0fe\",\"114\":\"#4285f4\",\"117\":\"#4285f4\",\"118\":\"#1a73e8\",\"121\":\"#4285f4\",\"126\":\"#e8f0fe\",\"127\":\"#d2e3fc\",\"128\":\"#4285f4\",\"129\":\"#1a73e8\",\"130\":\"#fce8e6\",\"131\":\"#fad2cf\",\"134\":\"#d93025\",\"140\":\"#d93025\",\"144\":\"#d93025\",\"147\":\"#ea4335\",\"149\":\"#a50e0e\",\"150\":\"#fef7e0\",\"166\":\"#fbbc04\",\"169\":\"#ea8600\",\"171\":\"#e6f4ea\",\"180\":\"#188038\",\"187\":\"#34a853\",\"188\":\"#1e8e3e\",\"189\":\"#188038\",\"190\":\"#137333\",\"191\":\"#0d652d\",\"192\":\"rgba(0,0,0,.1)\",\"193\":\"rgba(0,0,0,.2)\",\"196\":\"rgba(255,255,255,0)\",\"197\":\"rgba(0,0,0,.12)\",\"198\":\"rgba(32,33,36,0)\",\"199\":\"rgba(32,33,36,.1)\",\"200\":\"rgba(0,0,0,.12)\",\"201\":\"rgba(0,0,0,.5)\",\"203\":\"#000\",\"204\":\"rgba(255,255,255,.5)\",\"205\":\"#1558d6\",\"207\":\"rgba(0,0,0,.24)\",\"208\":\"#f8f9fa\",\"209\":\"rgba(255,255,255,.6)\",\"210\":\"#1e8e3e\",\"211\":\"rgba(0,0,0,.02)\",\"212\":\"#000\",\"214\":\"rgba(0,0,0,.7)\",\"215\":\"#1a73e8\",\"216\":\"#d93025\",\"217\":\"#4285f4\",\"218\":\"rgba(0,0,0,.15)\",\"219\":\"rgba(0,0,0,.05)\",\"220\":\"#70757a\",\"221\":\"#dadce0\",\"222\":\"#188038\",\"223\":\"rgba(0,0,0,.6)\",\"224\":\"#34a853\",\"225\":\"rgba(255,255,255,.3)\",\"226\":\"rgba(0,0,0,.05)\",\"227\":\"rgba(0,0,0,.05)\",\"228\":\"rgba(32,33,36,.9)\",\"229\":\"rgba(255,255,255,.6)\",\"230\":\"rgba(0,0,0,.08)\",\"231\":\"rgba(255,255,255,.8)\",\"232\":\"rgba(0,0,0,.05)\",\"233\":\"#4285f4\",\"234\":\"rgba(0,0,0,.16)\",\"235\":\"#fff\",\"236\":\"rgba(0,0,0,.87)\",\"238\":\"#fdd663\",\"239\":\"#fdd663\",\"243\":\"#fdd663\",\"244\":\"rgba(255,255,255,.54)\",\"246\":\"rgba(0,0,0,.26)\",\"247\":\"rgba(0,0,0,.26)\",\"248\":\"rgba(0,0,0,.38)\",\"249\":\"rgba(0,0,0,.03)\",\"250\":\"#4285f4\",\"251\":\"rgba(60,64,67,.12)\",\"252\":\"rgba(255,255,255,0)\",\"253\":\"rgba(0,0,0,0)\",\"256\":\"#3c4043\",\"257\":\"#d2e3fc\",\"258\":\"#d2e3fc\",\"259\":\"#4285f4\",\"261\":\"rgba(0,0,0,.16)\",\"262\":\"rgba(255,255,255,.3)\",\"263\":\"rgba(0,0,0,0)\",\"264\":\"#c5221f\",\"265\":\"#dadce0\",\"266\":\"#ea4335\",\"267\":\"#34a853\",\"268\":\"rgba(60,64,67,.15)\",\"269\":\"rgba(19,115,51,.15)\",\"270\":\"rgba(0,0,0,.15)\",\"271\":\"rgba(0,0,0,.18)\",\"272\":\"rgba(0,0,0,.28)\",\"273\":\"rgba(60,64,67,.3)\",\"274\":\"#1558d6\",\"275\":\"rgba(218,220,224,0)\",\"276\":\"rgba(218,220,224,0.5)\",\"277\":\"rgba(0,0,0,.26)\",\"278\":\"#81c995\"}]",
			"rkD25": "%.@.[[\"hl\",\"ja-JP\"]]]",
			"WiLzZe": "%.@.\"#202124\",\"#70757a\",null,null,\"#fff\",\"rgba(255,255,255,.70)\",28,24,26,20,16,-2,0,-4,2,0,0,24,20,20,14,12]",
			"AYkLRe": "%.@.\"20px\",20,\"14px\",14,\"\\\"rgba(0, 0, 0, .87)\\\"\"]",
			"rNyuJc": "",
			"LU5fGb": false,
			"gXkHoe": "105250506097979753968",
			"hevonc": "%.@.1]",
			"sBvdwb": "%.@.\"rgba(26,73,232,0.1)\",\"rgba(26,73,232,0.03)\",\"rgba(0,0,0,0.05)\",\"1.3\"]",
			"xcljyb": "%.@.\"8px\",8]"
		};
	})();
	(function() {
		google.ldi = {};
		google.pim = {};
		google.ldie = [];
		(function() {
			var a = google.ldi || {},
				b = google.pim || {},
				c;
			for (c in a)
				if (a.hasOwnProperty(c)) {
					c in b && (a[c] = b[c]);
					var d = document.getElementById(c) || document.documentElement.querySelector(
						'img[data-iid="' + c + '"]');
					d && Number(d.getAttribute("data-atf")) & 1 && (d.setAttribute(
						"data-deferred", "2"), d.src = a[c])
				};
		}).call(this);
	})();
	(function() {
		for (var a = document.getElementsByTagName("img"), b = 0, c = a.length; b <
			c; ++b) {
			var d = a[b],
				e;
			if (e = Number(d.getAttribute("data-atf")) & 1) {
				var f = d.getAttribute("jscontroller");
				e = (f === "UBXHI" || f === "R3fhkb" || f === "TSZEqd") && d.hasAttribute(
					"data-src")
			}
			e && (d.src = d.getAttribute("data-src"))
		};
	}).call(this);
	(function() {
		var b = function(a) {
			var c = 0;
			return function() {
				return c < a.length ? {
					done: !1,
					value: a[c++]
				} : {
					done: !0
				}
			}
		};
		var e = this || self;
		var g, h;
		a: {
			for (var k = ["CLOSURE_FLAGS"], l = e, n = 0; n < k.length; n++)
				if (l = l[k[n]], l == null) {
					h = null;
					break a
				}
			h = l
		}
		var p = h && h[610401301];
		g = p != null ? p : !1;
		var q, r = e.navigator;
		q = r ? r.userAgentData || null : null;

		function t(a) {
			return g ? q ? q.brands.some(function(c) {
				return (c = c.brand) && c.indexOf(a) != -1
			}) : !1 : !1
		}

		function u(a) {
			var c;
			a: {
				if (c = e.navigator)
					if (c = c.userAgent) break a;
				c = ""
			}
			return c.indexOf(a) != -1
		};

		function v() {
			return g ? !!q && q.brands.length > 0 : !1
		}

		function w() {
			return u("Safari") && !(x() || (v() ? 0 : u("Coast")) || (v() ? 0 : u(
					"Opera")) || (v() ? 0 : u("Edge")) || (v() ? t("Microsoft Edge") : u(
					"Edg/")) || (v() ? t("Opera") : u("OPR")) || u("Firefox") || u("FxiOS") ||
				u("Silk") || u("Android"))
		}

		function x() {
			return v() ? t("Chromium") : (u("Chrome") || u("CriOS")) && !(v() ? 0 : u(
				"Edge")) || u("Silk")
		}

		function y() {
			return u("Android") && !(x() || u("Firefox") || u("FxiOS") || (v() ? 0 : u(
				"Opera")) || u("Silk"))
		};
		var z = v() ? !1 : u("Trident") || u("MSIE");
		y();
		x();
		w();
		var A = !z && !w(),
			D = function(a) {
				if (/-[a-z]/.test("ved")) return null;
				if (A && a.dataset) {
					if (y() && !("ved" in a.dataset)) return null;
					a = a.dataset.ved;
					return a === void 0 ? null : a
				}
				return a.getAttribute("data-" + "ved".replace(/([A-Z])/g, "-$1").toLowerCase())
			};
		var E = [],
			F = null;

		function G(a) {
			a = a.target;
			var c = performance.now(),
				f = [],
				H = f.concat,
				d = E;
			if (!(d instanceof Array)) {
				var m = typeof Symbol != "undefined" && Symbol.iterator && d[Symbol.iterator];
				if (m) d = m.call(d);
				else if (typeof d.length == "number") d = {
					next: b(d)
				};
				else throw Error("b`" + String(d));
				for (var B = []; !(m = d.next()).done;) B.push(m.value);
				d = B
			}
			E = H.call(f, d, [c]);
			if (a && a instanceof HTMLElement)
				if (a === F) {
					if (c = E.length >= 4) c = (E[E.length - 1] - E[E.length - 4]) / 1E3 < 5;
					if (c) {
						c = google.getEI(a);
						a.hasAttribute("data-ved") ? f = a ? D(a) || "" : "" : f = (f =
							a.closest("[data-ved]")) ? D(f) || "" : "";
						f = f || "";
						if (a.hasAttribute("jsname")) a = a.getAttribute("jsname");
						else {
							var C;
							a = (C = a.closest("[jsname]")) == null ? void 0 : C.getAttribute(
								"jsname")
						}
						google.log("rcm", "&ei=" + c + "&tgtved=" + f + "&jsname=" + (a || ""))
					}
				} else F = a, E = [c]
		}
		window.document.addEventListener("DOMContentLoaded", function() {
			document.body.addEventListener("click", G)
		});
	}).call(this);
	var w = function(a) {
		var b = 0;
		return function() {
			return b < a.length ? {
				done: !1,
				value: a[b++]
			} : {
				done: !0
			}
		}
	};
	window.jsl = window.jsl || {};
	window.jsl.dh = function(a, b, m) {
		try {
			var h = document.getElementById(a),
				e;
			if (!h && ((e = google.stvsc) == null ? 0 : e.dds)) {
				e = [];
				var f = e.concat,
					c = google.stvsc.dds;
				if (c instanceof Array) var n = c;
				else {
					var p = typeof Symbol != "undefined" && Symbol.iterator && c[Symbol.iterator];
					if (p) var g = p.call(c);
					else if (typeof c.length == "number") g = {
						next: w(c)
					};
					else throw Error(String(c) + " is not an iterable or ArrayLike");
					c = g;
					var q;
					for (g = []; !(q = c.next()).done;) g.push(q.value);
					n = g
				}
				var r = f.call(e, n);
				for (f = 0; f < r.length && !(h = r[f].getElementById(a)); f++);
			}
			if (h) h.innerHTML = b, m && m();
			else {
				var d = {
					id: a,
					script: String(!!m),
					milestone: String(google.jslm || 0)
				};
				google.jsla && (d.async = google.jsla);
				var t = a.indexOf("_"),
					k = t > 0 ? a.substring(0, t) : "",
					u = document.createElement("div");
				u.innerHTML = b;
				var l = u.children[0];
				if (l && (d.tag = l.tagName, d["class"] = String(l.className || null), d.name =
						String(l.getAttribute("jsname")), k)) {
					a = [];
					var v = document.querySelectorAll('[id^="' + k + '_"]');
					for (b = 0; b < v.length; ++b) a.push(v[b].id);
					d.ids = a.join(",")
				}
				google.ml(Error(k ? "Missing ID with prefix " +
					k : "Missing ID"), !1, d)
			}
		} catch (x) {
			google.ml(x, !0, {
				"jsl.dh": !0
			})
		}
	};
	(function() {
		var x = true;
		google.jslm = x ? 2 : 1;
	})();
	google.x(null, function() {
		(function() {
			(function() {
				google.csct = {};
				google.csct.ps = 'AOvVaw0-f2fjNTlG1-6OYrqp7a-I&ust=1723974058185097';
			})();
		})();
		(function() {
			(function() {
				google.csct.rw = true;
			})();
		})();
		(function() {
			window.jsl = window.jsl || {};
			window.jsl.dh = window.jsl.dh || function(i, c, d) {
				try {
					var e = document.getElementById(i);
					if (e) {
						e.innerHTML = c;
						if (d) {
							d();
						}
					} else {
						if (window.jsl.el) {
							window.jsl.el(new Error('Missing ID.'), {
								'id': i
							});
						}
					}
				} catch (e) {
					if (window.jsl.el) {
						window.jsl.el(new Error('jsl.dh'));
					}
				}
			};
		})();
		(function() {
			window.jsl.dh('spch',
				'<style>.spch-dlg{background:transparent;border:none}.spch{background:var(--xhUGwc);height:100%;left:0;opacity:0;overflow:hidden;position:fixed;text-align:left;top:0;visibility:hidden;width:100%;z-index:10000;transition:visibility 0s linear 0.218s,background-color 0.218s;}.s2fp.spch{opacity:1;transition-delay:0s;visibility:visible;}.pz5bj{background:none;border:none;color:var(--IXoxUe);cursor:pointer;font-size:26px;right:0;line-height:15px;opacity:.6;margin:-1px -1px 0 0;padding:0 0 2px 0;height:48px;width:48px;position:absolute;top:0;z-index:10}.pz5bj:hover{opacity:.8}.pz5bj:active{opacity:1}.spchc{display:block;height:42px;pointer-events:none;margin:auto;position:relative;top:0;margin-top:312px;max-width:572px;min-width:534px;padding:0 223px}.inner-container{height:100%;opacity:.1;pointer-events:none;width:100%;transition:opacity .318s ease-in;}.s2ml .inner-container,.s2ra .inner-container,.s2er .inner-container,.OJaju .inner-container{opacity:1;transition:opacity 0s}</style><style>.google-logo{background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALwAAABACAQAAAAKENVCAAAI/ElEQVR4Ae3ae3BU5RnH8e/ZTbIhhIRbRIJyCZcEk4ZyE4RBAiRBxRahEZBLQYUZAjIgoLUWB6wjKIK2MtAqOLVUKSqWQW0ZaOQq0IFAIZVrgFQhXAOShITEbHY7407mnPfc8u6ya2f0fN6/9rzvc87Z39nbed/l/8OhIKMDQ+hHKp1JJB6FKq5QQhH72MZ1IsDRhvkU4bds9WxlLNE4wqg9q6jBL9G+4knc/HB9qXmuG4goD89TjT+IVkimE/zt6sYh/EG3WmaiOMGHbgQ38YfY3ibKCV6GMabHWY0bo+Ps5jjnuYlCczrSk8Hcgd5U1rONoDnG48Ova2W8RGeMXAxiHfWakT4mOx81oRiG1/C5vYh47KSx5fZid4JvxxVd7MdIp3EK06kNNXYneIWtutgLaIasQUwkJE7wE3SxbycWR8SD93BOiL2YRBwRDN5FwOPchaqecZQTQQ4XAApz0FrFQSLPwQD8mlZNEt8L5841D62/cJVIi2cgPelEAlBOCYfYSxXymjKAXqSQAFRwloPspRp5dzOMHiTThEqK2c1OvGHIsg/30YUWKHzDKfZwEB+2xBn3gUSSwmA+MpluruYDySMPYD23TOrX0V/q+CPZYai+yHw8wKscbmhMD+IVfyevcMlkuvxXxGOphTD4Gi4iJ40C/DZtM12wk8Lfbes/oSN27mGPZW0RnVmvebxIMng3z1Bluddz5Mh9wm8icqZIzPHfZDxW8qhotL6cUVh5zP74XOBg0MEnsgW/bfMxzyIOYdgSIuV5/JJtPmZmSlb7mI6ZGTLVQQafSKHUvp7BxFxhSD6N8UsH4An5aT+J3mNB1T+K3hj8YQ/ezRbpvY3CYKEwYFLYgvfTkQZ9qTN8nS3lIdJJZwTLDdNztfwUrTTDp+hllmnqrxo+sLqi1dWwuFPKYnK5h0we5c/UhhT8fF1FHWsZTis8dGAyB4S+67RF5wVhwC/DGHxvAqI4Imyv50Vi0YpjsW4l4AAuGii63yE+lhCHVlOW6o79TxRN/ee64y/SHb8TO4MOvq3uYh6iO1oufiP0r0VnjtA9K4zBDzSdgKtjJGbyqBfG5dFguC62sZiZoLt0Qy3qvYzCKIZNQQYvXupdxGO0Rni5dLebl1wexuD7A4DuC+gprMwTxu2hwT+E7c9iZYEw7lMaiBPeczAXT3EQwcdwTbP1Eq3RiyaPvcIe/4igj9C5NYzBpwOQKmzbh4IVF4dMviOShHfCEdxYieKY8M5qCUCy8E4oxIWVnwcRfK4wdhqitiyk1JBHJc3UU4UT+HDRYADR1GEnB2s9WYrqssn41/BjxcdrrEOVzRogS4hqOfVY8fI6qzWXYTAbgRwUVMvwYeUzzpKCnMGobvIeDRTuZyajiMLoMG2oRONfwnV5kNDNFH5ZKAD8SbPtFrHYaSr8+nkLgCXC53sCdloJz+RlAFYJv5bisPOG9Cv+U+F+O6AZM4Sx2iz+QKZxWrgArSmEbiAIpwvQGdV/qMFOFUdRdTbUn6QCO9c4bajvJhy/GjuFyOqEqhhIZyUXWEk6esd4imTyKTIG/1e08kghNNEMR7WfgERUpTTmPKrmIdSXGupbiHu3dQFZCagy2MGXzCAekZcPySKDlVSYTwsf5QB9aeBiCWMJxcO0RPU5AW5UPuyJI9xhr/diz4ssF6ohGJXyFmu42Fj5MrTGMILgKTyHqpoCAipR3YE9cURFWOorUCVhrzWyKrFWwGg68hIXG79uGziG1rt0IFhPcC+qj6gioARVJm7sRPMTVCWG+u54sBNHqm19Ji7sZCDrv5gp53ekkcNGvHJvGB+zdVd+M60JRi/eREt9VIQqgfuxM5Q4VEcM9R5ysfMAUaA78iFUzRmIfb2sw+j9m6m042lOEqS1hv+R3Y2svpSJCxJCn9hjR5ztywSgg7BtGwpWFHYLY+8CIB2/5Jppj5BvoE7Qz/a8bCVSrIv+quQrYCLVQl0NXVEpnBF6f4aVX+guvELAPmH7GMk/ZX1BgKJb2szBnEJBEMFHUyY841SsjGcr7bGVabLC8z6dsJPC3ww1sxE9LfTeoAdmeumOPkNzYcUb776Y6aebOh5Hg6m6l1MaZhYGOUn2sjD6MAmYyeIWfiqYhoKNLJNlaC/ryCUGvRhyWUedYfx7KIiack4XfZ5ujMI4XewlxIpzMEL04w31k3STtEW4NWd6Uugr4yFEHt4Ielo4iRvC+P20R6QwTZPnFtpjI4dKi5veAlbwLPnM4NesZDs3Tcd9RgxGIw3jdjCeO1FQSGYiuw39D6A1CJ+u/wsm0pZA/STDEnY9A9DKMtRvZjStAIVOzOJMSAsh+YaMltGXGEChHVPYr+s/igsbPTmHP8T2IR7MvW46voZa0+2voLfAor7GdPtz6C0yHVfNt4S+9KewwXTJ8xtumWyv5T6w14pNIYTu40VcWHHzvvSe3sWFnsIq6foVKCb1qyOw2N2EnZJ7+5aRSFAYS2lQp3maLOy5WS61pyW4MKOwCJ/E5X8BBTMuXsW+tpITQQYPcXws8Zyuk420eOZyQSqqy8zDg4yH+cp2T2cYjp1sim3rTzEEO4/YPKNL9AvpD00K+ZTbnZXwc1KSh9FspNrmDbSZicQirwmzLMI7Qb7EnjxM57hp/TGmEUNjEljAZUNtHW/TGvhA+J6QCx4gicVcNT2r7TyIgoEiGf+99CeVLiTSDKimjK85QSH7qCJ4Cr0YRi9SaI6fG5zlIAUcwS9d34Nsen9Xz3f1hRRQJF0fzVCyyaQdcZRzil18zCUAPtHc3s3mTYIRzWCGkEEH4vFSxmn2s5kSJDgOGP/l4Ii8aOHetzeOsIhiNAX0wVq28O3lwXHbklnIeQJ/PHJhQbh72YXjts3Eq4n0t5h7BL+mzcVx29Kpxy9E70IvV5h7qiEJRxiswC+0feTgJkAhg3d098S/J8IUfhziOUAaouscoYJmpNIO0WXSuYYjLLpxFb9U85KNI4wyKJWKfQKOMEtmm33sXCCbCHC4mMxZIWpx/aglEeNwM4J3KNb8jvmaDTxBIt8jhR8vD22IpYYr1PBD5HA4HP8DxVcxdwELEFUAAAAASUVORK5CYII=) no-repeat center;background-size:94px 32px;height:32px;width:94px;top:8px;opacity:0;float:right;left:255px;pointer-events:none;position:relative;transition:opacity .5s ease-in,left .5s ease-in}</style><button class=\"pz5bj\" id=\"spchx\" aria-label=\"閉じる\"><span style=\"height:16px;line-height:16px;width:16px\" class=\"z1asCe wuXmqc\"><svg focusable=\"false\" xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 24 24\"><path d=\"M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z\"></path></svg></span></button><div class=\"spchc\" id=\"spchc\"><div class=\"inner-container\"><div class=\"button-container\"><style>.LgbsSe{background-color:#fff;border:1px solid #f8f9fa;border-radius:100%;bottom:0;box-shadow:0 2px 5px rgba(0,0,0,.1);cursor:pointer;display:inline-block;opacity:0;pointer-events:none;position:absolute;right:0;transition:background-color 0.218s,border 0.218s,box-shadow 0.218s;transition-delay:0;position:absolute;opacity:0;left:0;top:0}.s2fp .LgbsSe{opacity:1;pointer-events:auto;transform:scale(1);}.s2ra .LgbsSe{background-color:#ea4335;border:0;box-shadow:none}.r8s4j{background-color:#dadce0;border-radius:100%;display:inline-block;opacity:1;pointer-events:none;position:absolute;transform:scale(.01);transition:opacity 0.218s;height:301px;left:-69px;top:-69px;width:301px;}.button-container{pointer-events:none;position:relative;transition:transform 0.218s,opacity 0.218s ease-in;transform:scale(.1);height:165px;width:165px;right:-70px;top:-70px;float:right;}.s2fp .button-container{transform:scale(1)}.s2ra .LgbsSe:active{background-color:#c5221f}.LgbsSe:active{background-color:#f8f9fa}</style><span class=\"r8s4j\" id=\"spchl\"></span><span class=\"LgbsSe\" id=\"spchb\"><div class=\"microphone\"><style>.microphone{height:87px;pointer-events:none;position:absolute;width:42px;top:47px;transform:scale(1);left:43px;}.receiver{background-color:#999;border-radius:30px;height:46px;left:25px;pointer-events:none;position:absolute;width:24px}.wrapper{bottom:0;height:53px;left:11px;overflow:hidden;pointer-events:none;position:absolute;width:52px}.stem{background-color:#999;bottom:14px;height:14px;left:22px;pointer-events:none;position:absolute;width:9px;z-index:1}.shell{border:7px solid #999;border-radius:28px;bottom:27px;height:57px;pointer-events:none;position:absolute;width:38px;z-index:0;left:0px}.s2ml .receiver,.s2ml .stem{background-color:#f44}.s2ml .shell{border-color:#f44}.s2ra .receiver,.s2ra .stem{background-color:#fff}.s2ra .shell{border-color:#fff}</style><span class=\"receiver\"></span><div class=\"wrapper\"><span class=\"stem\"></span><span class=\"shell\"></span></div></div></span></div><div class=\"text-container\"><style>.text-container{pointer-events:none;position:absolute;}.spcht{font-weight:normal;line-height:1.2;opacity:0;pointer-events:none;position:absolute;text-align:left;-webkit-font-smoothing:antialiased;transition:opacity .1s ease-in,margin-left .5s ease-in,top 0s linear 0.218s;left:-44px;top:-.2em;margin-left:44px;font-size:32px;width:460px;}.s2fp .spcht{margin-left:0;opacity:1;transition:opacity .5s ease-out,margin-left .5s ease-out}.spchta{color:var(--JKqx2);cursor:pointer;font-size:18px;font-weight:500;pointer-events:auto;text-decoration:underline}.spch-2l.spcht,.spch-3l.spcht,.spch-4l.spcht{transition:top 0.218s ease-out}.spch-2l.spcht{top:-.6em}.spch-3l.spcht{top:-1.3em}.spch-4l.spcht{top:-1.7em}.s2fp .spch-5l.spcht{top:-2.5em;}</style><span class=\"spcht\" style=\"color:#70757a\" id=\"spchi\"></span><span class=\"spcht\" style=\"color:#000\" id=\"spchf\"></span></div><div class=\"google-logo\"></div></div><div class=\"permission-bar\"><style>.permission-bar{margin-top:-100px;opacity:0;pointer-events:none;position:absolute;width:500px;transition:opacity 0.218s ease-in,margin-top .4s ease-in}.s2wfp .permission-bar{margin-top:-300px;opacity:1;transition:opacity .5s ease-out 0.218s,margin-top 0.218s ease-out 0.218s}.permission-bar-gradient{box-shadow:0 1px 0px #4285f4;height:80px;left:0;margin:0;opacity:0;pointer-events:none;position:fixed;right:0;top:-80px;transition:opacity 0.218s,box-shadow 0.218s}.s2wfp .permission-bar-gradient{box-shadow:0 1px 80px #4285f4;opacity:1;pointer-events:none;animation:allow-alert .75s 0 infinite;animation-direction:alternate;animation-timing-function:ease-out;transition:opacity 0.218s,box-shadow 0.218s}@-webkit-keyframes allow-alert {from{opacity:1}to{opacity:.35}}</style><div class=\"permission-bar-gradient\"></div></div></div>'
			);
		})();
		(function() {
			window.jsl.dh('_KnDAZtO4CObk2roP-pvLiAs_6',
				'<style>.YB4h9{background-color:var(--TMYS9);color:var(--EpFNW);padding:18px 60px 18px 12px;position:relative}.C85rO{font-size:20px}.Gtr0ne{padding-top:10px}.zYSLYb{}.YB4h9 .Gtr0ne .zYSLYb{color:var(--EpFNW);text-decoration:underline}.YB4h9 .Job8vb{padding:20px;position:absolute;right:0;top:0}.YB4h9.rPPJbd .Job8vb{padding-top:24px;padding-right:8px;position:absolute;right:0;top:0}.YB4h9.q7XNbb{margin-bottom:44px}.YB4h9.JF7fk{border-radius:16px;border-style:solid;border-color:var(--gS5jXb)}.YB4h9.IPINXd{border-bottom-left-radius:16px;border-bottom-right-radius:16px;border-color:var(--gS5jXb);border-style:solid;border-top:none}.YB4h9.rPPJbd{background-color:var(--xhUGwc);color:var(--bbQxAb)}.YB4h9.rPPJbd .zYSLYb{color:var(--bbQxAb);text-decoration:underline}.R4GmFb{align-items:center;display:flex;flex-direction:row;margin-bottom:8px}.R4GmFb svg{display:block}.JrWcR{margin-left:10px}</style><span class=\"Job8vb z1asCe wuXmqc\" aria-label=\"フィードバックをお送りいただけるものを選択してください を閉じる\" role=\"button\" tabindex=\"0\" jsaction=\"kEOk4d\" style=\"height:20px;line-height:20px;width:20px\" data-ved=\"0ahUKEwjT9fv73fuHAxVmslYBHfrNErEQmIkGCAs\"><svg focusable=\"false\" xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 24 24\"><path d=\"M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z\"></path></svg></span><div class=\"C85rO\" aria-level=\"1\" role=\"heading\">フィードバックをお送りいただけるものを選択してください</div>'
			);
		})();
		(function() {
			google.drty && google.drty(undefined, true);
		})();
	});
	if (!google.stvsc) {
		google.drty && google.drty(undefined, true);
	}

	</script>
	<script src="./いんでっくす_files/m=sb_wiz,aa,abd,sytu,sytt,syto,syg0,syts,sytf,syzz,syz5,sytj,syz4,syu9,sytd,syua,syub,syu2,syu0,syu3,syu4,sytx,syty,sytq,sytp,sytr,sytn,syu6,sytk,sytg,syth,sys6,syrw,syru,syrt,sytw,syz3,syui,syuj,syuh,async,ifl,pHXghd,sf,sy1"
	nonce="" async="" gapi_processed="true"></script>
	<link href="./いんでっくす_files/m=sy1g2,P10Owf,sy1eu,sy1es,syrb,gSZvdb,syzu,syzt,WlNQGd,syrg,syrd,syrc,syra,DPreE,sy106,sy104,nabPbb,syzo,syzm,syjx,syl2,CnSW2d,kQvlef,sy105,fXO0xe"
	rel="preload" as="script" fetchpriority="low">
	<script src="./いんでっくす_files/m=sy1g2,P10Owf,sy1eu,sy1es,syrb,gSZvdb,syzu,syzt,WlNQGd,syrg,syrd,syrc,syra,DPreE,sy106,sy104,nabPbb,syzo,syzm,syjx,syl2,CnSW2d,kQvlef,sy105,fXO0xe"
	nonce="" async=""></script>
	<link href="./いんでっくす_files/m=syfz,aLUfP" rel="preload" as="script" fetchpriority="low">
	<script src="./いんでっくす_files/m=syfz,aLUfP" nonce="" async=""></script>
	<link href="./いんでっくす_files/m=kMFpHd,sy8w,bm51tf" rel="preload" as="script"
	fetchpriority="low">
	<script src="./いんでっくす_files/m=kMFpHd,sy8w,bm51tf" nonce="" async=""></script>
</body>

</html>
