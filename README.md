<html lang="en-US">
    <head><meta charset="UTF-8"><script type="text/javascript" async="" src="https://www.googletagmanager.com/gtag/js?id=AW-11381883891&amp;l=dataLayer&amp;cx=c&amp;gtm=45Pe51e0v9171239473za200"></script><script async="" src="https://connect.facebook.net/en_US/fbevents.js"></script><script>if(navigator.userAgent.match(/MSIE|Internet Explorer/i)||navigator.userAgent.match(/Trident\/7\..*?rv:11/i)){var href=document.location.href;if(!href.match(/[?&]nowprocket/)){if(href.indexOf("?")==-1){if(href.indexOf("#")==-1){document.location.href=href+"?nowprocket=1"}else{document.location.href=href.replace("#","?nowprocket=1#")}}else{if(href.indexOf("#")==-1){document.location.href=href+"&nowprocket=1"}else{document.location.href=href.replace("#","&nowprocket=1#")}}}}</script><script>class RocketLazyLoadScripts{constructor(){this.triggerEvents=["keydown","mousedown","mousemove","touchmove","touchstart","touchend","wheel"],this.userEventHandler=this._triggerListener.bind(this),this.touchStartHandler=this._onTouchStart.bind(this),this.touchMoveHandler=this._onTouchMove.bind(this),this.touchEndHandler=this._onTouchEnd.bind(this),this.clickHandler=this._onClick.bind(this),this.interceptedClicks=[],window.addEventListener("pageshow",(e=>{this.persisted=e.persisted})),window.addEventListener("DOMContentLoaded",(()=>{this._preconnect3rdParties()})),this.delayedScripts={normal:[],async:[],defer:[]},this.allJQueries=[]}_addUserInteractionListener(e){document.hidden?e._triggerListener():(this.triggerEvents.forEach((t=>window.addEventListener(t,e.userEventHandler,{passive:!0}))),window.addEventListener("touchstart",e.touchStartHandler,{passive:!0}),window.addEventListener("mousedown",e.touchStartHandler),document.addEventListener("visibilitychange",e.userEventHandler))}_removeUserInteractionListener(){this.triggerEvents.forEach((e=>window.removeEventListener(e,this.userEventHandler,{passive:!0}))),document.removeEventListener("visibilitychange",this.userEventHandler)}_onTouchStart(e){"HTML"!==e.target.tagName&&(window.addEventListener("touchend",this.touchEndHandler),window.addEventListener("mouseup",this.touchEndHandler),window.addEventListener("touchmove",this.touchMoveHandler,{passive:!0}),window.addEventListener("mousemove",this.touchMoveHandler),e.target.addEventListener("click",this.clickHandler),this._renameDOMAttribute(e.target,"onclick","rocket-onclick"))}_onTouchMove(e){window.removeEventListener("touchend",this.touchEndHandler),window.removeEventListener("mouseup",this.touchEndHandler),window.removeEventListener("touchmove",this.touchMoveHandler,{passive:!0}),window.removeEventListener("mousemove",this.touchMoveHandler),e.target.removeEventListener("click",this.clickHandler),this._renameDOMAttribute(e.target,"rocket-onclick","onclick")}_onTouchEnd(e){window.removeEventListener("touchend",this.touchEndHandler),window.removeEventListener("mouseup",this.touchEndHandler),window.removeEventListener("touchmove",this.touchMoveHandler,{passive:!0}),window.removeEventListener("mousemove",this.touchMoveHandler)}_onClick(e){e.target.removeEventListener("click",this.clickHandler),this._renameDOMAttribute(e.target,"rocket-onclick","onclick"),this.interceptedClicks.push(e),e.preventDefault(),e.stopPropagation(),e.stopImmediatePropagation()}_replayClicks(){window.removeEventListener("touchstart",this.touchStartHandler,{passive:!0}),window.removeEventListener("mousedown",this.touchStartHandler),this.interceptedClicks.forEach((e=>{e.target.dispatchEvent(new MouseEvent("click",{view:e.view,bubbles:!0,cancelable:!0}))}))}_renameDOMAttribute(e,t,n){e.hasAttribute&&e.hasAttribute(t)&&(event.target.setAttribute(n,event.target.getAttribute(t)),event.target.removeAttribute(t))}_triggerListener(){this._removeUserInteractionListener(this),"loading"===document.readyState?document.addEventListener("DOMContentLoaded",this._loadEverythingNow.bind(this)):this._loadEverythingNow()}_preconnect3rdParties(){let e=[];document.querySelectorAll("script[type=rocketlazyloadscript]").forEach((t=>{if(t.hasAttribute("src")){const n=new URL(t.src).origin;n!==location.origin&&e.push({src:n,crossOrigin:t.crossOrigin||"module"===t.getAttribute("data-rocket-type")})}})),e=[...new Map(e.map((e=>[JSON.stringify(e),e]))).values()],this._batchInjectResourceHints(e,"preconnect")}async _loadEverythingNow(){this.lastBreath=Date.now(),this._delayEventListeners(),this._delayJQueryReady(this),this._handleDocumentWrite(),this._registerAllDelayedScripts(),this._preloadAllScripts(),await this._loadScriptsFromList(this.delayedScripts.normal),await this._loadScriptsFromList(this.delayedScripts.defer),await this._loadScriptsFromList(this.delayedScripts.async);try{await this._triggerDOMContentLoaded(),await this._triggerWindowLoad()}catch(e){}window.dispatchEvent(new Event("rocket-allScriptsLoaded")),this._replayClicks()}_registerAllDelayedScripts(){document.querySelectorAll("script[type=rocketlazyloadscript]").forEach((e=>{e.hasAttribute("src")?e.hasAttribute("async")&&!1!==e.async?this.delayedScripts.async.push(e):e.hasAttribute("defer")&&!1!==e.defer||"module"===e.getAttribute("data-rocket-type")?this.delayedScripts.defer.push(e):this.delayedScripts.normal.push(e):this.delayedScripts.normal.push(e)}))}async _transformScript(e){return await this._littleBreath(),new Promise((t=>{const n=document.createElement("script");[...e.attributes].forEach((e=>{let t=e.nodeName;"type"!==t&&("data-rocket-type"===t&&(t="type"),n.setAttribute(t,e.nodeValue))})),e.hasAttribute("src")?(n.addEventListener("load",t),n.addEventListener("error",t)):(n.text=e.text,t());try{e.parentNode.replaceChild(n,e)}catch(e){t()}}))}async _loadScriptsFromList(e){const t=e.shift();return t?(await this._transformScript(t),this._loadScriptsFromList(e)):Promise.resolve()}_preloadAllScripts(){this._batchInjectResourceHints([...this.delayedScripts.normal,...this.delayedScripts.defer,...this.delayedScripts.async],"preload")}_batchInjectResourceHints(e,t){var n=document.createDocumentFragment();e.forEach((e=>{if(e.src){const i=document.createElement("link");i.href=e.src,i.rel=t,"preconnect"!==t&&(i.as="script"),e.getAttribute&&"module"===e.getAttribute("data-rocket-type")&&(i.crossOrigin=!0),e.crossOrigin&&(i.crossOrigin=e.crossOrigin),n.appendChild(i)}})),document.head.appendChild(n)}_delayEventListeners(){let e={};function t(t,n){!function(t){function n(n){return e[t].eventsToRewrite.indexOf(n)>=0?"rocket-"+n:n}e[t]||(e[t]={originalFunctions:{add:t.addEventListener,remove:t.removeEventListener},eventsToRewrite:[]},t.addEventListener=function(){arguments[0]=n(arguments[0]),e[t].originalFunctions.add.apply(t,arguments)},t.removeEventListener=function(){arguments[0]=n(arguments[0]),e[t].originalFunctions.remove.apply(t,arguments)})}(t),e[t].eventsToRewrite.push(n)}function n(e,t){let n=e[t];Object.defineProperty(e,t,{get:()=>n||function(){},set(i){e["rocket"+t]=n=i}})}t(document,"DOMContentLoaded"),t(window,"DOMContentLoaded"),t(window,"load"),t(window,"pageshow"),t(document,"readystatechange"),n(document,"onreadystatechange"),n(window,"onload"),n(window,"onpageshow")}_delayJQueryReady(e){let t=window.jQuery;Object.defineProperty(window,"jQuery",{get:()=>t,set(n){if(n&&n.fn&&!e.allJQueries.includes(n)){n.fn.ready=n.fn.init.prototype.ready=function(t){e.domReadyFired?t.bind(document)(n):document.addEventListener("rocket-DOMContentLoaded",(()=>t.bind(document)(n)))};const t=n.fn.on;n.fn.on=n.fn.init.prototype.on=function(){if(this[0]===window){function e(e){return e.split(" ").map((e=>"load"===e||0===e.indexOf("load.")?"rocket-jquery-load":e)).join(" ")}"string"==typeof arguments[0]||arguments[0]instanceof String?arguments[0]=e(arguments[0]):"object"==typeof arguments[0]&&Object.keys(arguments[0]).forEach((t=>{delete Object.assign(arguments[0],{[e(t)]:arguments[0][t]})[t]}))}return t.apply(this,arguments),this},e.allJQueries.push(n)}t=n}})}async _triggerDOMContentLoaded(){this.domReadyFired=!0,await this._littleBreath(),document.dispatchEvent(new Event("rocket-DOMContentLoaded")),await this._littleBreath(),window.dispatchEvent(new Event("rocket-DOMContentLoaded")),await this._littleBreath(),document.dispatchEvent(new Event("rocket-readystatechange")),await this._littleBreath(),document.rocketonreadystatechange&&document.rocketonreadystatechange()}async _triggerWindowLoad(){await this._littleBreath(),window.dispatchEvent(new Event("rocket-load")),await this._littleBreath(),window.rocketonload&&window.rocketonload(),await this._littleBreath(),this.allJQueries.forEach((e=>e(window).trigger("rocket-jquery-load"))),await this._littleBreath();const e=new Event("rocket-pageshow");e.persisted=this.persisted,window.dispatchEvent(e),await this._littleBreath(),window.rocketonpageshow&&window.rocketonpageshow({persisted:this.persisted})}_handleDocumentWrite(){const e=new Map;document.write=document.writeln=function(t){const n=document.currentScript,i=document.createRange(),r=n.parentElement;let o=e.get(n);void 0===o&&(o=n.nextSibling,e.set(n,o));const s=document.createDocumentFragment();i.setStart(s,0),s.appendChild(i.createContextualFragment(t)),r.insertBefore(s,o)}}async _littleBreath(){Date.now()-this.lastBreath>45&&(await this._requestAnimFrame(),this.lastBreath=Date.now())}async _requestAnimFrame(){return document.hidden?new Promise((e=>setTimeout(e))):new Promise((e=>requestAnimationFrame(e)))}static run(){const e=new RocketLazyLoadScripts;e._addUserInteractionListener(e)}}RocketLazyLoadScripts.run();</script>
	
		<title>PLANILHAS PERSONALIZADAS – Curso0nline</title><link rel="stylesheet" href="https://treinamentoonlinerdc.com.br/wp-content/cache/perfmatters/treinamentoonlinerdc.com.br/css/page-836.used.css?ver=1728503944" as="style"><link rel="stylesheet" id="perfmatters-used-css" href="https://treinamentoonlinerdc.com.br/wp-content/cache/perfmatters/treinamentoonlinerdc.com.br/css/page-836.used.css?ver=1728503944" media="all"><link rel="preload" href="//www.w3.org/2000/svg'%20viewBox='0%200%20768%20230'%3E%3C/svg%3E" as="image"><link rel="preload" href="//www.w3.org/2000/svg'%20viewBox='0%200%20800%2042'%3E%3C/svg%3E" as="image">
<meta name="robots" content="max-image-preview:large">
	<style>img:is([sizes="auto" i], [sizes^="auto," i]) { contain-intrinsic-size: 3000px 1500px }</style>
	
<!-- Google Tag Manager by PYS -->
<script data-cfasync="false" data-pagespeed-no-defer="">
	var pys_datalayer_name = "dataLayer";
	window.dataLayer = window.dataLayer || [];</script> 
<!-- End Google Tag Manager by PYS -->
<script>
dataLayer = [{"title":"PLANILHAS PERSONALIZADAS","author":"rodrigodionizio84","wordcount":694,"logged_in":"false","page_id":836,"post_date":"2024-02-10 15:26:55","post_type":"page"}];
</script>
<link href="https://www.googletagmanager.com" rel="preconnect"><link href="https://treinamentoonlinerdc.com.br/wp-includes/js/jquery/jquery.min.js?ver=3.7.1" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/plugins/pixelyoursite/dist/scripts/jquery.bind-first-0.2.3.min.js?ver=6.7.1" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/plugins/pixelyoursite/dist/scripts/js.cookie-2.1.3.min.js?ver=2.1.3" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/plugins/pixelyoursite/dist/scripts/tld.min.js?ver=2.3.1" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/pixelyoursite/dist/scripts/public.js?ver=1730199689" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/ele-custom-skin/assets/js/ecs_ajax_pagination.js?ver=1730199689" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/ele-custom-skin/assets/js/ecs.js?ver=1730199689" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/super-links/assets/js/automatic-links.js?ver=1730199689" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/assets/js/hello-frontend.min.js?ver=3.2.1" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/js/webpack.runtime.min.js?ver=3.26.4" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/js/frontend-modules.min.js?ver=3.26.4" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-includes/js/jquery/ui/core.min.js?ver=1.13.3" rel="preload" as="script"><link href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/js/frontend.min.js?ver=3.26.4" rel="preload" as="script"><link href="https://www.googletagmanager.com/gtag/js?id=GT-PB6MS5Q" rel="preload" as="script"><link href="https://www.googletagmanager.com/gtag/js?id=AW-11381883891" rel="preload" as="script"><link href="https://www.googletagmanager.com/gtag/js?id=AW-11381883891" rel="preload" as="script"><script type="text/javascript" async="" src="https://googleads.g.doubleclick.net/pagead/viewthroughconversion/11381883891/?random=1736902296269&amp;cv=11&amp;fst=1736902296269&amp;bg=ffffff&amp;guid=ON&amp;async=1&amp;gtm=45Pe51e0v9171239473za200&amp;gcd=13l3l3l3l1l1&amp;dma=0&amp;tag_exp=101925629~102067555~102067808~102081485~102198178&amp;u_w=1920&amp;u_h=1080&amp;url=https%3A%2F%2Ftreinamentoonlinerdc.com.br%2Fplanilhas-personalizadas%2F&amp;hn=www.googleadservices.com&amp;frm=0&amp;tiba=PLANILHAS%20PERSONALIZADAS%20%E2%80%93%20Curso0nline&amp;npa=0&amp;pscdl=noapi&amp;auid=303689764.1736900473&amp;uaa=x86&amp;uab=64&amp;uafvl=Google%2520Chrome%3B131.0.6778.265%7CChromium%3B131.0.6778.265%7CNot_A%2520Brand%3B24.0.0.0&amp;uamb=0&amp;uam=&amp;uap=Windows&amp;uapv=19.0.0&amp;uaw=0&amp;fledge=1&amp;data=event%3Dgtag.config&amp;rfmt=3&amp;fmt=4"></script><script src="https://treinamentoonlinerdc.com.br/wp-includes/js/wp-emoji-release.min.js?ver=6.7.1" defer=""></script></head><body class="page-template page-template-elementor_canvas page page-id-836 wp-embed-responsive elementor-default elementor-template-canvas elementor-kit-91 elementor-page elementor-page-836 e--ua-blink e--ua-chrome e--ua-webkit" data-elementor-device-mode="tablet">GTM-PQ7M2P9D<script type="application/javascript" id="pys-version-script">console.log('PixelYourSite Free version 10.0.3.1');</script>
<link rel="dns-prefetch" href="//maps.googleapis.com">
<link rel="dns-prefetch" href="//maps.gstatic.com">


<link rel="dns-prefetch" href="//ajax.googleapis.com">
<link rel="dns-prefetch" href="//apis.google.com">
<link rel="dns-prefetch" href="//google-analytics.com">
<link rel="dns-prefetch" href="//www.google-analytics.com">
<link rel="dns-prefetch" href="//ssl.google-analytics.com">
<link rel="dns-prefetch" href="//youtube.com">
<link rel="dns-prefetch" href="//api.pinterest.com">
<link rel="dns-prefetch" href="//cdnjs.cloudflare.com">
<link rel="dns-prefetch" href="//connect.facebook.net">
<link rel="dns-prefetch" href="//platform.twitter.com">
<link rel="dns-prefetch" href="//syndication.twitter.com">
<link rel="dns-prefetch" href="//platform.instagram.com">
<link rel="dns-prefetch" href="//disqus.com">
<link rel="dns-prefetch" href="//sitename.disqus.com">
<link rel="dns-prefetch" href="//s7.addthis.com">
<link rel="dns-prefetch" href="//platform.linkedin.com">
<link rel="dns-prefetch" href="//w.sharethis.com">
<link rel="dns-prefetch" href="//i0.wp.com">
<link rel="dns-prefetch" href="//i1.wp.com">
<link rel="dns-prefetch" href="//i2.wp.com">
<link rel="dns-prefetch" href="//stats.wp.com">
<link rel="dns-prefetch" href="//pixel.wp.com">
<link rel="dns-prefetch" href="//s.gravatar.com">
<link rel="dns-prefetch" href="//0.gravatar.com">
<link rel="dns-prefetch" href="//2.gravatar.com">
<link rel="dns-prefetch" href="//1.gravatar.com">
<link rel="dns-prefetch" href="//www.googletagmanager.com">
<link rel="dns-prefetch" href="//googletagmanager.com">
<link rel="alternate" type="application/rss+xml" title="Curso0nline » Feed" href="https://treinamentoonlinerdc.com.br/feed/">
<link rel="alternate" type="application/rss+xml" title="Curso0nline » Comments Feed" href="https://treinamentoonlinerdc.com.br/comments/feed/">
<script>
window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.0.3\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.0.3\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/treinamentoonlinerdc.com.br\/wp-includes\/js\/wp-emoji-release.min.js?ver=6.7.1"}};
/*! This file is auto-generated */
!function(i,n){var o,s,e;function c(e){try{var t={supportTests:e,timestamp:(new Date).valueOf()};sessionStorage.setItem(o,JSON.stringify(t))}catch(e){}}function p(e,t,n){e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(t,0,0);var t=new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data),r=(e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(n,0,0),new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data));return t.every(function(e,t){return e===r[t]})}function u(e,t,n){switch(t){case"flag":return n(e,"\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f","\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f")?!1:!n(e,"\ud83c\uddfa\ud83c\uddf3","\ud83c\uddfa\u200b\ud83c\uddf3")&&!n(e,"\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f","\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");case"emoji":return!n(e,"\ud83d\udc26\u200d\u2b1b","\ud83d\udc26\u200b\u2b1b")}return!1}function f(e,t,n){var r="undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?new OffscreenCanvas(300,150):i.createElement("canvas"),a=r.getContext("2d",{willReadFrequently:!0}),o=(a.textBaseline="top",a.font="600 32px Arial",{});return e.forEach(function(e){o[e]=t(a,e,n)}),o}function t(e){var t=i.createElement("script");t.src=e,t.defer=!0,i.head.appendChild(t)}"undefined"!=typeof Promise&&(o="wpEmojiSettingsSupports",s=["flag","emoji"],n.supports={everything:!0,everythingExceptFlag:!0},e=new Promise(function(e){i.addEventListener("DOMContentLoaded",e,{once:!0})}),new Promise(function(t){var n=function(){try{var e=JSON.parse(sessionStorage.getItem(o));if("object"==typeof e&&"number"==typeof e.timestamp&&(new Date).valueOf()<e.timestamp+604800&&"object"==typeof e.supportTests)return e.supportTests}catch(e){}return null}();if(!n){if("undefined"!=typeof Worker&&"undefined"!=typeof OffscreenCanvas&&"undefined"!=typeof URL&&URL.createObjectURL&&"undefined"!=typeof Blob)try{var e="postMessage("+f.toString()+"("+[JSON.stringify(s),u.toString(),p.toString()].join(",")+"));",r=new Blob([e],{type:"text/javascript"}),a=new Worker(URL.createObjectURL(r),{name:"wpTestEmojiSupports"});return void(a.onmessage=function(e){c(n=e.data),a.terminate(),t(n)})}catch(e){}c(n=f(s,u,p))}t(n)}).then(function(e){for(var t in e)n.supports[t]=e[t],n.supports.everything=n.supports.everything&&n.supports[t],"flag"!==t&&(n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&n.supports[t]);n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&!n.supports.flag,n.DOMReady=!1,n.readyCallback=function(){n.DOMReady=!0}}).then(function(){return e}).then(function(){var e;n.supports.everything||(n.readyCallback(),(e=n.source||{}).concatemoji?t(e.concatemoji):e.wpemoji&&e.twemoji&&(t(e.twemoji),t(e.wpemoji)))}))}((window,document),window._wpemojiSettings);
</script>
<style id="wp-emoji-styles-inline-css">

	img.wp-smiley, img.emoji {
		display: inline !important;
		border: none !important;
		box-shadow: none !important;
		height: 1em !important;
		width: 1em !important;
		margin: 0 0.07em !important;
		vertical-align: -0.1em !important;
		background: none !important;
		padding: 0 !important;
	}
</style>
<style id="global-styles-inline-css">
:root{--wp--preset--aspect-ratio--square: 1;--wp--preset--aspect-ratio--4-3: 4/3;--wp--preset--aspect-ratio--3-4: 3/4;--wp--preset--aspect-ratio--3-2: 3/2;--wp--preset--aspect-ratio--2-3: 2/3;--wp--preset--aspect-ratio--16-9: 16/9;--wp--preset--aspect-ratio--9-16: 9/16;--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:root { --wp--style--global--content-size: 800px;--wp--style--global--wide-size: 1200px; }:where(body) { margin: 0; }.wp-site-blocks > .alignleft { float: left; margin-right: 2em; }.wp-site-blocks > .alignright { float: right; margin-left: 2em; }.wp-site-blocks > .aligncenter { justify-content: center; margin-left: auto; margin-right: auto; }:where(.wp-site-blocks) > * { margin-block-start: 24px; margin-block-end: 0; }:where(.wp-site-blocks) > :first-child { margin-block-start: 0; }:where(.wp-site-blocks) > :last-child { margin-block-end: 0; }:root { --wp--style--block-gap: 24px; }:root :where(.is-layout-flow) > :first-child{margin-block-start: 0;}:root :where(.is-layout-flow) > :last-child{margin-block-end: 0;}:root :where(.is-layout-flow) > *{margin-block-start: 24px;margin-block-end: 0;}:root :where(.is-layout-constrained) > :first-child{margin-block-start: 0;}:root :where(.is-layout-constrained) > :last-child{margin-block-end: 0;}:root :where(.is-layout-constrained) > *{margin-block-start: 24px;margin-block-end: 0;}:root :where(.is-layout-flex){gap: 24px;}:root :where(.is-layout-grid){gap: 24px;}.is-layout-flow > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}.is-layout-flow > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}.is-layout-flow > .aligncenter{margin-left: auto !important;margin-right: auto !important;}.is-layout-constrained > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}.is-layout-constrained > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}.is-layout-constrained > .aligncenter{margin-left: auto !important;margin-right: auto !important;}.is-layout-constrained > :where(:not(.alignleft):not(.alignright):not(.alignfull)){max-width: var(--wp--style--global--content-size);margin-left: auto !important;margin-right: auto !important;}.is-layout-constrained > .alignwide{max-width: var(--wp--style--global--wide-size);}body .is-layout-flex{display: flex;}.is-layout-flex{flex-wrap: wrap;align-items: center;}.is-layout-flex > :is(*, div){margin: 0;}body .is-layout-grid{display: grid;}.is-layout-grid > :is(*, div){margin: 0;}body{padding-top: 0px;padding-right: 0px;padding-bottom: 0px;padding-left: 0px;}a:where(:not(.wp-element-button)){text-decoration: underline;}:root :where(.wp-element-button, .wp-block-button__link){background-color: #32373c;border-width: 0;color: #fff;font-family: inherit;font-size: inherit;line-height: inherit;padding: calc(0.667em + 2px) calc(1.333em + 2px);text-decoration: none;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}
:root :where(.wp-block-pullquote){font-size: 1.5em;line-height: 1.6;}
</style>
<link rel="stylesheet" id="hello-elementor-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/style.min.css?ver=3.2.1" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/style.min.css?ver=3.2.1">
<link rel="stylesheet" id="hello-elementor-theme-style-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/theme.min.css?ver=3.2.1" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/theme.min.css?ver=3.2.1">
<link rel="stylesheet" id="hello-elementor-header-footer-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/header-footer.min.css?ver=3.2.1" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/header-footer.min.css?ver=3.2.1">
<link rel="stylesheet" id="elementor-frontend-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/frontend.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/frontend.min.css?ver=3.26.4">
<link rel="stylesheet" id="elementor-post-91-css" href="https://treinamentoonlinerdc.com.br/wp-content/uploads/elementor/css/post-91.css?ver=1736273746" media="all">
<link rel="stylesheet" id="widget-image-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-image.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-image.min.css?ver=3.26.4">
<link rel="stylesheet" id="widget-heading-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-heading.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-heading.min.css?ver=3.26.4">
<link rel="stylesheet" id="widget-text-editor-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-text-editor.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-text-editor.min.css?ver=3.26.4">
<link rel="stylesheet" id="e-animation-grow-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/lib/animations/styles/e-animation-grow.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/lib/animations/styles/e-animation-grow.min.css?ver=3.26.4">
<link rel="stylesheet" id="widget-icon-list-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-icon-list.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-icon-list.min.css?ver=3.26.4">
<link rel="stylesheet" id="widget-icon-box-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-icon-box.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-icon-box.min.css?ver=3.26.4">
<link rel="stylesheet" id="widget-menu-anchor-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-menu-anchor.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-menu-anchor.min.css?ver=3.26.4">
<link rel="stylesheet" id="widget-toggle-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-toggle.min.css?ver=3.26.4" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/css/widget-toggle.min.css?ver=3.26.4">
<link rel="stylesheet" id="elementor-post-836-css" href="https://treinamentoonlinerdc.com.br/wp-content/uploads/elementor/css/post-836.css?ver=1736274030" media="all">
<link data-minify="1" rel="stylesheet" id="ecs-styles-css" data-pmdelayedstyle="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/ele-custom-skin/assets/css/ecs-style.css?ver=1736273900" media="all" href="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/ele-custom-skin/assets/css/ecs-style.css?ver=1736273900">
<style id="rocket-lazyload-inline-css">
.rll-youtube-player{position:relative;padding-bottom:56.23%;height:0;overflow:hidden;max-width:100%;}.rll-youtube-player:focus-within{outline: 2px solid currentColor;outline-offset: 5px;}.rll-youtube-player iframe{position:absolute;top:0;left:0;width:100%;height:100%;z-index:100;background:0 0}.rll-youtube-player img{bottom:0;display:block;left:0;margin:auto;max-width:100%;width:100%;position:absolute;right:0;top:0;border:none;height:auto;-webkit-transition:.4s all;-moz-transition:.4s all;transition:.4s all}.rll-youtube-player img:hover{-webkit-filter:brightness(75%)}.rll-youtube-player .play{height:100%;width:100%;left:0;top:0;position:absolute;background:url(https://treinamentoonlinerdc.com.br/wp-content/plugins/wp-rocket/assets/img/youtube.png) no-repeat center;background-color: transparent !important;cursor:pointer;border:none;}.wp-embed-responsive .wp-has-aspect-ratio .rll-youtube-player{position:absolute;padding-bottom:0;width:100%;height:100%;top:0;bottom:0;left:0;right:0}
</style>

<script src="https://treinamentoonlinerdc.com.br/wp-includes/js/jquery/jquery.min.js?ver=3.7.1" id="jquery-core-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" id="jquery-migrate-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/plugins/pixelyoursite/dist/scripts/jquery.bind-first-0.2.3.min.js?ver=6.7.1" id="jquery-bind-first-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/plugins/pixelyoursite/dist/scripts/js.cookie-2.1.3.min.js?ver=2.1.3" id="js-cookie-pys-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/plugins/pixelyoursite/dist/scripts/tld.min.js?ver=2.3.1" id="js-tld-js"></script>
<script id="pys-js-extra">
var pysOptions = {"staticEvents":{"facebook":{"init_event":[{"delay":0,"type":"static","name":"PageView","pixelIds":["908259174143698"],"eventID":"6a9ca772-cbc0-4032-941f-9d645002a3ef","params":{"page_title":"PLANILHAS PERSONALIZADAS","post_type":"page","post_id":836,"plugin":"PixelYourSite","user_role":"guest","event_url":"treinamentoonlinerdc.com.br\/planilhas-personalizadas\/"},"e_id":"init_event","ids":[],"hasTimeWindow":false,"timeWindow":0,"woo_order":"","edd_order":""}]}},"dynamicEvents":[],"triggerEvents":[],"triggerEventTypes":[],"facebook":{"pixelIds":["908259174143698"],"advancedMatching":[],"advancedMatchingEnabled":false,"removeMetadata":false,"contentParams":{"post_type":"page","post_id":836,"content_name":"PLANILHAS PERSONALIZADAS"},"commentEventEnabled":true,"wooVariableAsSimple":false,"downloadEnabled":true,"formEventEnabled":true,"serverApiEnabled":false,"wooCRSendFromServer":false,"send_external_id":null},"debug":"","siteUrl":"https:\/\/treinamentoonlinerdc.com.br","ajaxUrl":"https:\/\/treinamentoonlinerdc.com.br\/wp-admin\/admin-ajax.php","ajax_event":"21d0fb4ce8","enable_remove_download_url_param":"1","cookie_duration":"7","last_visit_duration":"60","enable_success_send_form":"","ajaxForServerEvent":"1","ajaxForServerStaticEvent":"1","send_external_id":"1","external_id_expire":"180","track_cookie_for_subdomains":"1","google_consent_mode":"1","gdpr":{"ajax_enabled":false,"all_disabled_by_api":false,"facebook_disabled_by_api":false,"analytics_disabled_by_api":false,"google_ads_disabled_by_api":false,"pinterest_disabled_by_api":false,"bing_disabled_by_api":false,"externalID_disabled_by_api":false,"facebook_prior_consent_enabled":true,"analytics_prior_consent_enabled":true,"google_ads_prior_consent_enabled":null,"pinterest_prior_consent_enabled":true,"bing_prior_consent_enabled":true,"cookiebot_integration_enabled":false,"cookiebot_facebook_consent_category":"marketing","cookiebot_analytics_consent_category":"statistics","cookiebot_tiktok_consent_category":"marketing","cookiebot_google_ads_consent_category":null,"cookiebot_pinterest_consent_category":"marketing","cookiebot_bing_consent_category":"marketing","consent_magic_integration_enabled":false,"real_cookie_banner_integration_enabled":false,"cookie_notice_integration_enabled":false,"cookie_law_info_integration_enabled":false,"analytics_storage":{"enabled":true,"value":"granted","filter":false},"ad_storage":{"enabled":true,"value":"granted","filter":false},"ad_user_data":{"enabled":true,"value":"granted","filter":false},"ad_personalization":{"enabled":true,"value":"granted","filter":false}},"cookie":{"disabled_all_cookie":false,"disabled_start_session_cookie":false,"disabled_advanced_form_data_cookie":false,"disabled_landing_page_cookie":false,"disabled_first_visit_cookie":false,"disabled_trafficsource_cookie":false,"disabled_utmTerms_cookie":false,"disabled_utmId_cookie":false},"tracking_analytics":{"TrafficSource":"direct","TrafficLanding":"undefined","TrafficUtms":[],"TrafficUtmsId":[]},"GATags":{"ga_datalayer_type":"default","ga_datalayer_name":"dataLayerPYS"},"woo":{"enabled":false},"edd":{"enabled":false},"cache_bypass":"1736361390"};
</script>
<script data-minify="1" src="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/pixelyoursite/dist/scripts/public.js?ver=1730199689" id="pys-js"></script>
<script id="ecs_ajax_load-js-extra">
var ecs_ajax_params = {"ajaxurl":"https:\/\/treinamentoonlinerdc.com.br\/wp-admin\/admin-ajax.php","posts":"{\"page\":0,\"pagename\":\"planilhas-personalizadas\",\"error\":\"\",\"m\":\"\",\"p\":0,\"post_parent\":\"\",\"subpost\":\"\",\"subpost_id\":\"\",\"attachment\":\"\",\"attachment_id\":0,\"name\":\"planilhas-personalizadas\",\"page_id\":0,\"second\":\"\",\"minute\":\"\",\"hour\":\"\",\"day\":0,\"monthnum\":0,\"year\":0,\"w\":0,\"category_name\":\"\",\"tag\":\"\",\"cat\":\"\",\"tag_id\":\"\",\"author\":\"\",\"author_name\":\"\",\"feed\":\"\",\"tb\":\"\",\"paged\":0,\"meta_key\":\"\",\"meta_value\":\"\",\"preview\":\"\",\"s\":\"\",\"sentence\":\"\",\"title\":\"\",\"fields\":\"\",\"menu_order\":\"\",\"embed\":\"\",\"category__in\":[],\"category__not_in\":[],\"category__and\":[],\"post__in\":[],\"post__not_in\":[],\"post_name__in\":[],\"tag__in\":[],\"tag__not_in\":[],\"tag__and\":[],\"tag_slug__in\":[],\"tag_slug__and\":[],\"post_parent__in\":[],\"post_parent__not_in\":[],\"author__in\":[],\"author__not_in\":[],\"search_columns\":[],\"post_type\":[\"post\",\"page\",\"e-landing-page\"],\"ignore_sticky_posts\":false,\"suppress_filters\":false,\"cache_results\":true,\"update_post_term_cache\":true,\"update_menu_item_cache\":false,\"lazy_load_term_meta\":true,\"update_post_meta_cache\":true,\"posts_per_page\":10,\"nopaging\":false,\"comments_per_page\":\"50\",\"no_found_rows\":false,\"order\":\"DESC\"}"};
</script>
<script data-minify="1" src="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/ele-custom-skin/assets/js/ecs_ajax_pagination.js?ver=1730199689" id="ecs_ajax_load-js"></script>
<script data-minify="1" src="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/ele-custom-skin/assets/js/ecs.js?ver=1730199689" id="ecs-script-js"></script>
<link rel="https://api.w.org/" href="https://treinamentoonlinerdc.com.br/wp-json/"><link rel="alternate" title="JSON" type="application/json" href="https://treinamentoonlinerdc.com.br/wp-json/wp/v2/pages/836"><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://treinamentoonlinerdc.com.br/xmlrpc.php?rsd">
<meta name="generator" content="WordPress 6.7.1">
<link rel="canonical" href="https://treinamentoonlinerdc.com.br/planilhas-personalizadas/">
<link rel="shortlink" href="https://treinamentoonlinerdc.com.br/?p=836">
<link rel="alternate" title="oEmbed (JSON)" type="application/json+oembed" href="https://treinamentoonlinerdc.com.br/wp-json/oembed/1.0/embed?url=https%3A%2F%2Ftreinamentoonlinerdc.com.br%2Fplanilhas-personalizadas%2F">
<link rel="alternate" title="oEmbed (XML)" type="text/xml+oembed" href="https://treinamentoonlinerdc.com.br/wp-json/oembed/1.0/embed?url=https%3A%2F%2Ftreinamentoonlinerdc.com.br%2Fplanilhas-personalizadas%2F&amp;format=xml">
<!-- HFCM by 99 Robots - Snippet # 1: Tags google ads AW-11381883891 -->
<!-- Google tag (gtag.js) -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=GT-PB6MS5Q"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'GT-PB6MS5Q');
</script>

<!-- /end HFCM by 99 Robots -->
<!-- HFCM by 99 Robots - Snippet # 2: google tags AW-11381883891 -->
<!-- Google tag (gtag.js) -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=AW-11381883891"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-11381883891');
</script>
<!-- /end HFCM by 99 Robots -->
<!-- HFCM by 99 Robots - Snippet # 3: TAG GOOGLE ADS -->
<!-- Google tag (gtag.js) -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=AW-11381883891"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-11381883891');
</script>
<!-- /end HFCM by 99 Robots -->
treinamentoonlinerdc.com.br<meta name="facebook-domain-verification" content="lv0g0b6yvh8wga3edzpmemyq4kfl94"><meta name="generator" content="Elementor 3.26.4; features: e_font_icon_svg, additional_custom_breakpoints; settings: css_print_method-external, google_font-enabled, font_display-auto">
			<style>
				.e-con.e-parent:nth-of-type(n+4):not(.e-lazyloaded):not(.e-no-lazyload),
				.e-con.e-parent:nth-of-type(n+4):not(.e-lazyloaded):not(.e-no-lazyload) * {
					background-image: none !important;
				}
				@media screen and (max-height: 1024px) {
					.e-con.e-parent:nth-of-type(n+3):not(.e-lazyloaded):not(.e-no-lazyload),
					.e-con.e-parent:nth-of-type(n+3):not(.e-lazyloaded):not(.e-no-lazyload) * {
						background-image: none !important;
					}
				}
				@media screen and (max-height: 640px) {
					.e-con.e-parent:nth-of-type(n+2):not(.e-lazyloaded):not(.e-no-lazyload),
					.e-con.e-parent:nth-of-type(n+2):not(.e-lazyloaded):not(.e-no-lazyload) * {
						background-image: none !important;
					}
				}
			</style>
			<noscript><style id="rocket-lazyload-nojs-css">.rll-youtube-player, [data-lazy-src]{display:none !important;}</style></noscript>	<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">

	PQ7M2P9D		<div data-elementor-type="wp-page" data-elementor-id="836" class="elementor elementor-836">
						<section class="elementor-section elementor-top-section elementor-element elementor-element-6334e16c elementor-reverse-tablet elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="6334e16c" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-3980fba4" data-id="3980fba4" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-6afd96d3 elementor-widget elementor-widget-image" data-id="6afd96d3" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img data-perfmatters-preload="" fetchpriority="high" decoding="async" width="768" height="230" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-768x230.png" class="attachment-medium_large size-medium_large wp-image-673 entered lazyloaded" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-768x230.png 768w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-300x90.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-1024x307.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-1536x461.png 1536w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2.png 1666w" data-lazy-sizes="(max-width: 768px) 100vw, 768px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-768x230.png" data-ll-status="loaded" sizes="(max-width: 768px) 100vw, 768px" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-768x230.png 768w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-300x90.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-1024x307.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-1536x461.png 1536w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2.png 1666w"><noscript><img fetchpriority="high" decoding="async" width="768" height="230" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-768x230.png" class="attachment-medium_large size-medium_large wp-image-673" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-768x230.png 768w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-300x90.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-1024x307.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2-1536x461.png 1536w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Copia-de-ATENCAO-Preencha-os-SEUS-dados-corretamente-para-ter-acesso-ao-treinamento.-Antes-de-efetuar-a-compra.-reveja-os-dados-NOME-CPF-e-EMAIL.-2.png 1666w" sizes="(max-width: 768px) 100vw, 768px" /></noscript>															</div>
				</div>
				<div class="elementor-element elementor-element-3ee6a77c elementor-widget elementor-widget-html" data-id="3ee6a77c" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
					
				</div>
				</div>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-575a5c52 elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="575a5c52" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-6ba3679d" data-id="6ba3679d" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-247be9f2 elementor-widget__width-initial elementor-widget-mobile__width-initial elementor-widget elementor-widget-heading" data-id="247be9f2" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"></h2><h2 class="elementor-heading-title elementor-size-default elementor-inline-editing pen" data-elementor-setting-key="title" data-pen-placeholder="Type Here..." style="text-align: center">PLANILHAS PARA UM ANO DE TREINO. <span>AJUSTADOS DE ACORDO COM O SEU BIOTIPO.</span></h2>				</div>
				</div>
				<div class="elementor-element elementor-element-6d4ed1b3 elementor-widget elementor-widget-text-editor" data-id="6d4ed1b3" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p><b><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">AVISO: </span></span></span></span></span></span></b> <span style="font-weight: 400;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Você está a um passo de&nbsp; ter um plano de treino personalizado. Chega de passar horas e horas pesquisando quais os melhores exercícios&nbsp;</span></span></span></span></span></span></span></p>								</div>
				</div>
				<div class="elementor-element elementor-element-7e23dc47 elementor-align-justify elementor-mobile-align-justify elementor-tablet-align-center elementor-widget elementor-widget-button" data-id="7e23dc47" data-element_type="widget" id="SIM , QUERO COMEÇAR AGORA" data-widget_type="button.default">
				<div class="elementor-widget-container">
									<div class="elementor-button-wrapper">
					<a class="elementor-button elementor-button-link elementor-size-sm elementor-animation-grow" href="#PRECO">
						<span class="elementor-button-content-wrapper">
									<span class="elementor-button-text">baixar AS  PLANILHAS + bônus </span>
					</span>
					</a>
				</div>
								</div>
				</div>
				<div class="elementor-element elementor-element-a144721 elementor-widget elementor-widget-image" data-id="a144721" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
																<a href="https://pay.hotmart.com/V71259759F?checkoutMode=10">
							<img data-perfmatters-preload="" decoding="async" width="800" height="42" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png" class="attachment-large size-large wp-image-444 entered lazyloaded" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w" data-lazy-sizes="(max-width: 800px) 100vw, 800px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png" data-ll-status="loaded" sizes="(max-width: 800px) 100vw, 800px" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w"><noscript><img decoding="async" width="800" height="42" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png" class="attachment-large size-large wp-image-444" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w" sizes="(max-width: 800px) 100vw, 800px" /></noscript>								</a>
															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-25c9657d" data-id="25c9657d" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
							</div>
		</div>
					</div>
		</section>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-7aad5ca4 elementor-reverse-tablet elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7aad5ca4" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-334e7a73" data-id="334e7a73" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-2dc8307b elementor-widget elementor-widget-heading" data-id="2dc8307b" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">treinos personalizados como phat (power hypertrophy adaptive training) , upper/lower push/pull , fullbody , metabólico <span style="color:#FF0033">e muito mais ...
</span></h2>				</div>
				</div>
				<div class="elementor-element elementor-element-bcb8105 elementor-widget-mobile__width-initial elementor-widget__width-initial elementor-widget elementor-widget-heading" data-id="bcb8105" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">Treinos focados em cada grupamento muscular é o fim das dúvidas sobre volume e alteração de treino. <br><br>Nós temos um método validado por diversos clientes. Vamos te ensinar a não depender das fichinhas de academia .<br>


</h2>				</div>
				</div>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-30c9f04 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="30c9f04" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-inner-column elementor-element elementor-element-3ff3e331" data-id="3ff3e331" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-468aac54 elementor-widget elementor-widget-image" data-id="468aac54" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="800" height="800" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-1024x1024.png" class="attachment-large size-large wp-image-789 entered lazyloaded" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-768x768.png 768w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1.png 1080w" data-lazy-sizes="(max-width: 800px) 100vw, 800px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-1024x1024.png" data-ll-status="loaded" sizes="(max-width: 800px) 100vw, 800px" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-768x768.png 768w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1.png 1080w"><noscript><img decoding="async" width="800" height="800" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-1024x1024.png" class="attachment-large size-large wp-image-789" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1-768x768.png 768w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-2-1.png 1080w" sizes="(max-width: 800px) 100vw, 800px" /></noscript>															</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<div class="elementor-element elementor-element-622a5e9c elementor-widget elementor-widget-heading" data-id="622a5e9c" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">CHEGA DE TREINO QUE NÃO FUNCIONA.</h2>				</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-56218a70 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="56218a70" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4017b634" data-id="4017b634" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-28e8001b elementor-widget elementor-widget-heading" data-id="28e8001b" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">Nas planilhas  você vai encontrar métodos exclusivos e que funcionam para ajudá-lo a atingir seus objetivos.<br><br>com  treinos personalizados para iniciantes , intermediários e avançados. </h2>				</div>
				</div>
				<div class="elementor-element elementor-element-51c7beab elementor-widget elementor-widget-text-editor" data-id="51c7beab" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p><strong><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">CHEGA DE DEPENDER DE FICHINHAS DA ACADEMIA!</span></span></strong></p><p><strong><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">&nbsp;</span></span></strong></p>								</div>
				</div>
				<div class="elementor-element elementor-element-169314fe elementor-align-center elementor-mobile-align-center elementor-tablet-align-center elementor-widget elementor-widget-button" data-id="169314fe" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
									<div class="elementor-button-wrapper">
					<a class="elementor-button elementor-button-link elementor-size-sm elementor-animation-grow" href="https://pay.kiwify.com.br/42jap0q">
						<span class="elementor-button-content-wrapper">
									<span class="elementor-button-text">sim, quero as planilhas </span>
					</span>
					</a>
				</div>
								</div>
				</div>
				<div class="elementor-element elementor-element-6301e66 elementor-widget elementor-widget-image" data-id="6301e66" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
																<a href="https://pay.hotmart.com/V71259759F?checkoutMode=10">
							<img data-perfmatters-preload="" decoding="async" width="800" height="42" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20800%2042'%3E%3C/svg%3E" class="attachment-large size-large wp-image-444" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w" data-lazy-sizes="(max-width: 800px) 100vw, 800px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png"><noscript><img decoding="async" width="800" height="42" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png" class="attachment-large size-large wp-image-444" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w" sizes="(max-width: 800px) 100vw, 800px" /></noscript>								</a>
															</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-48f7ef3e elementor-reverse-tablet elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="48f7ef3e" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-748b0995" data-id="748b0995" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-48fad63b elementor-widget elementor-widget-heading" data-id="48fad63b" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">INDICADO PARA ...</h2>				</div>
				</div>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-760ebe8e elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="760ebe8e" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-5c028aa5" data-id="5c028aa5" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-6fe23baf elementor-widget elementor-widget-image" data-id="6fe23baf" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="1080" height="1080" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201080%201080'%3E%3C/svg%3E" class="attachment-full size-full wp-image-675" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-768x768.png 768w" data-lazy-sizes="(max-width: 1080px) 100vw, 1080px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1.png"><noscript><img loading="lazy" decoding="async" width="1080" height="1080" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1.png" class="attachment-full size-full wp-image-675" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-1-768x768.png 768w" sizes="(max-width: 1080px) 100vw, 1080px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-ac7a169" data-id="ac7a169" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-382c047f elementor-widget elementor-widget-heading" data-id="382c047f" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">ALUNO INICIANTE </h2>				</div>
				</div>
				<div class="elementor-element elementor-element-70ab17a2 elementor-widget elementor-widget-text-editor" data-id="70ab17a2" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>Se você não sabe qual treino seguir e qual aparelho é melhor. Agora você tem a solução.</p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-1136c94c elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="1136c94c" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-73a3a1d1" data-id="73a3a1d1" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-4a8f4030 elementor-widget elementor-widget-image" data-id="4a8f4030" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="1080" height="1080" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201080%201080'%3E%3C/svg%3E" class="attachment-full size-full wp-image-676" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-768x768.png 768w" data-lazy-sizes="(max-width: 1080px) 100vw, 1080px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2.png"><noscript><img loading="lazy" decoding="async" width="1080" height="1080" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2.png" class="attachment-full size-full wp-image-676" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-2-768x768.png 768w" sizes="(max-width: 1080px) 100vw, 1080px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-30f02b30" data-id="30f02b30" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-271f1e1e elementor-widget elementor-widget-heading" data-id="271f1e1e" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">PERSONAL TRAINER</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-1632c7b9 elementor-widget elementor-widget-text-editor" data-id="1632c7b9" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Personal você precisa ter uma variedade de treino para seus alunos e pode mandar para seus alunos a execução correta de cada máquina , pois temos os vídeos de cada execução.</span></span></p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-20acf1e6 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="20acf1e6" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-415db03b" data-id="415db03b" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-7b9dd1cd elementor-widget elementor-widget-image" data-id="7b9dd1cd" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="1080" height="1080" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201080%201080'%3E%3C/svg%3E" class="attachment-full size-full wp-image-677" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-768x768.png 768w" data-lazy-sizes="(max-width: 1080px) 100vw, 1080px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3.png"><noscript><img loading="lazy" decoding="async" width="1080" height="1080" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3.png" class="attachment-full size-full wp-image-677" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/MIDIAS-3-768x768.png 768w" sizes="(max-width: 1080px) 100vw, 1080px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-5e0e2796" data-id="5e0e2796" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-3dd3d464 elementor-widget elementor-widget-heading" data-id="3dd3d464" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">ALUNO AVANÇADO</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-27b01ea0 elementor-widget elementor-widget-text-editor" data-id="27b01ea0" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>Se você quer aumentar seus resultados e sair desse plator essa é a solução.</p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-67f2f25e elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="67f2f25e" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-32c42bde" data-id="32c42bde" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap">
							</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-5d207101" data-id="5d207101" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-434dc490 elementor-widget-mobile__width-initial elementor-widget elementor-widget-heading" data-id="434dc490" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">4 BÔNUS ESPECIAS</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-709f1466 elementor-widget elementor-widget-image" data-id="709f1466" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="341" height="340" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20341%20340'%3E%3C/svg%3E" class="attachment-full size-full wp-image-329" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5.png 341w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5-150x150.png 150w" data-lazy-sizes="(max-width: 341px) 100vw, 341px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5.png"><noscript><img loading="lazy" decoding="async" width="341" height="340" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5.png" class="attachment-full size-full wp-image-329" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5.png 341w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2023/12/bolo-no-pote-artesanal-modulo-5-150x150.png 150w" sizes="(max-width: 341px) 100vw, 341px" /></noscript>															</div>
				</div>
				<div class="elementor-element elementor-element-8fc238a elementor-icon-list--layout-traditional elementor-list-item-link-full_width elementor-widget elementor-widget-icon-list" data-id="8fc238a" data-element_type="widget" data-widget_type="icon-list.default">
				<div class="elementor-widget-container">
							<ul class="elementor-icon-list-items">
							<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-chevron-circle-down" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M504 256c0 137-111 248-248 248S8 393 8 256 119 8 256 8s248 111 248 248zM273 369.9l135.5-135.5c9.4-9.4 9.4-24.6 0-33.9l-17-17c-9.4-9.4-24.6-9.4-33.9 0L256 285.1 154.4 183.5c-9.4-9.4-24.6-9.4-33.9 0l-17 17c-9.4 9.4-9.4 24.6 0 33.9L239 369.9c9.4 9.4 24.6 9.4 34 0z"></path></svg>						</span>
										<span class="elementor-icon-list-text">BÔNUS 1</span>
									</li>
						</ul>
						</div>
				</div>
				<div class="elementor-element elementor-element-794df342 elementor-widget elementor-widget-text-editor" data-id="794df342" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p><br></p>
<p>250 RECEITAS SAUDÁVEIS.</p>
<p>Chega de comer só batata , ovo e frango . Agora você vai aprender que dieta não precisa ser algo chato.</p>
<p></p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-730b2fd elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="730b2fd" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-7e75bd1f" data-id="7e75bd1f" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-ce1ba3d elementor-widget elementor-widget-image" data-id="ce1ba3d" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="1080" height="1080" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201080%201080'%3E%3C/svg%3E" class="attachment-full size-full wp-image-790" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-768x768.png 768w" data-lazy-sizes="(max-width: 1080px) 100vw, 1080px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3.png"><noscript><img loading="lazy" decoding="async" width="1080" height="1080" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3.png" class="attachment-full size-full wp-image-790" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-3-768x768.png 768w" sizes="(max-width: 1080px) 100vw, 1080px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-3e6c6e66" data-id="3e6c6e66" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-9e5ad61 elementor-icon-list--layout-traditional elementor-list-item-link-full_width elementor-widget elementor-widget-icon-list" data-id="9e5ad61" data-element_type="widget" data-widget_type="icon-list.default">
				<div class="elementor-widget-container">
							<ul class="elementor-icon-list-items">
							<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-chevron-circle-down" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M504 256c0 137-111 248-248 248S8 393 8 256 119 8 256 8s248 111 248 248zM273 369.9l135.5-135.5c9.4-9.4 9.4-24.6 0-33.9l-17-17c-9.4-9.4-24.6-9.4-33.9 0L256 285.1 154.4 183.5c-9.4-9.4-24.6-9.4-33.9 0l-17 17c-9.4 9.4-9.4 24.6 0 33.9L239 369.9c9.4 9.4 24.6 9.4 34 0z"></path></svg>						</span>
										<span class="elementor-icon-list-text">BÔNUS 2</span>
									</li>
						</ul>
						</div>
				</div>
				<div class="elementor-element elementor-element-1b6c397a elementor-widget elementor-widget-text-editor" data-id="1b6c397a" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>&nbsp;</p><p>DESAFIO 24 DIAS .</p><p>Uma metodologia personalizada para ajudar você adquirir um novo hábito&nbsp; em 24 dias. E assim conseguir seguir os treinos e a alimentação saudável .</p><p>&nbsp;</p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-16a41cf9 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="16a41cf9" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-3ce3201" data-id="3ce3201" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-17d4230f elementor-widget elementor-widget-image" data-id="17d4230f" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="1080" height="1080" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201080%201080'%3E%3C/svg%3E" class="attachment-full size-full wp-image-785" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-768x768.png 768w" data-lazy-sizes="(max-width: 1080px) 100vw, 1080px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1.png"><noscript><img loading="lazy" decoding="async" width="1080" height="1080" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1.png" class="attachment-full size-full wp-image-785" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/defined-abdomen-1-768x768.png 768w" sizes="(max-width: 1080px) 100vw, 1080px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-955df14" data-id="955df14" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-cd56737 elementor-icon-list--layout-traditional elementor-list-item-link-full_width elementor-widget elementor-widget-icon-list" data-id="cd56737" data-element_type="widget" data-widget_type="icon-list.default">
				<div class="elementor-widget-container">
							<ul class="elementor-icon-list-items">
							<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-chevron-circle-down" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M504 256c0 137-111 248-248 248S8 393 8 256 119 8 256 8s248 111 248 248zM273 369.9l135.5-135.5c9.4-9.4 9.4-24.6 0-33.9l-17-17c-9.4-9.4-24.6-9.4-33.9 0L256 285.1 154.4 183.5c-9.4-9.4-24.6-9.4-33.9 0l-17 17c-9.4 9.4-9.4 24.6 0 33.9L239 369.9c9.4 9.4 24.6 9.4 34 0z"></path></svg>						</span>
										<span class="elementor-icon-list-text">BÔNUS 3</span>
									</li>
						</ul>
						</div>
				</div>
				<div class="elementor-element elementor-element-16061ba6 elementor-widget elementor-widget-text-editor" data-id="16061ba6" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>&nbsp;</p><p><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">TREINO FUNCIONAL COM KETTELLEBEL.</span></span></span></span></span></span></span></span></p><p><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Faça treinos personalizados e focados em melhorar seu condicionamento físico e mental.</span></span></span></span></span></span></span></span></p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-6fee1604 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="6fee1604" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-54d65185" data-id="54d65185" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-42eddab elementor-widget elementor-widget-image" data-id="42eddab" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="300" height="250" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20250'%3E%3C/svg%3E" class="attachment-large size-large wp-image-878" alt="" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Design-sem-nome-12.png"><noscript><img loading="lazy" decoding="async" width="300" height="250" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/Design-sem-nome-12.png" class="attachment-large size-large wp-image-878" alt="" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-4c121b11" data-id="4c121b11" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-f273ec2 elementor-icon-list--layout-traditional elementor-list-item-link-full_width elementor-widget elementor-widget-icon-list" data-id="f273ec2" data-element_type="widget" data-widget_type="icon-list.default">
				<div class="elementor-widget-container">
							<ul class="elementor-icon-list-items">
							<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-chevron-circle-down" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M504 256c0 137-111 248-248 248S8 393 8 256 119 8 256 8s248 111 248 248zM273 369.9l135.5-135.5c9.4-9.4 9.4-24.6 0-33.9l-17-17c-9.4-9.4-24.6-9.4-33.9 0L256 285.1 154.4 183.5c-9.4-9.4-24.6-9.4-33.9 0l-17 17c-9.4 9.4-9.4 24.6 0 33.9L239 369.9c9.4 9.4 24.6 9.4 34 0z"></path></svg>						</span>
										<span class="elementor-icon-list-text">BÔNUS 4</span>
									</li>
						</ul>
						</div>
				</div>
				<div class="elementor-element elementor-element-7600531 elementor-widget elementor-widget-text-editor" data-id="7600531" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p style="color: #ffffff; font-family: Sora, sans-serif;"><br></p>
<div><span style="vertical-align: inherit;">&nbsp;</span><span style="color: #ffffff; font-family: Sora, sans-serif; font-weight: var( --e-global-typography-text-font-weight ); font-size: 1rem;">&nbsp;</span><span style="color: #ffffff; font-family: Sora, sans-serif; font-weight: var( --e-global-typography-text-font-weight ); font-size: 1rem;">&nbsp;VÍDEOS EXPLICANDO A EXECUÇÃO CORRETA EM CADA MÁQUINA.</span><br><span style="color: #ffffff; font-family: Sora, sans-serif; font-weight: var( --e-global-typography-text-font-weight ); font-size: 1rem;"><br></span></div>
<div><span style="color: #ffffff; font-family: Sora, sans-serif;">Chega de dúvida na execução de cada treino .</span><span style="color: #ffffff; font-family: Sora, sans-serif; font-weight: var( --e-global-typography-text-font-weight ); font-size: 1rem;"><br></span></div>
<p></p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<div class="elementor-element elementor-element-49c5f205 elementor-widget elementor-widget-image" data-id="49c5f205" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
																<a href="https://pay.hotmart.com/V71259759F?checkoutMode=10">
							<img data-perfmatters-preload="" decoding="async" width="800" height="42" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20800%2042'%3E%3C/svg%3E" class="attachment-large size-large wp-image-444" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w" data-lazy-sizes="(max-width: 800px) 100vw, 800px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png"><noscript><img decoding="async" width="800" height="42" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png" class="attachment-large size-large wp-image-444" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1.png 988w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-300x16.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/payments-logo-1-768x40.png 768w" sizes="(max-width: 800px) 100vw, 800px" /></noscript>								</a>
															</div>
				</div>
				<div class="elementor-element elementor-element-7b913a3c elementor-align-center elementor-mobile-align-center elementor-tablet-align-center elementor-widget elementor-widget-button" data-id="7b913a3c" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
									<div class="elementor-button-wrapper">
					<a class="elementor-button elementor-button-link elementor-size-sm elementor-animation-grow" href="https://pay.kiwify.com.br/42jap0q?afid=QpVn94hI">
						<span class="elementor-button-content-wrapper">
									<span class="elementor-button-text">sim, QUERO COMEÇAR AGORA!</span>
					</span>
					</a>
				</div>
								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-2befa9e3 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="2befa9e3" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-210b7c0" data-id="210b7c0" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-1a1805a6 elementor-widget elementor-widget-heading" data-id="1a1805a6" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">E SE EU NÃO GOSTAR ?
<div><br></div></h2>				</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-459a5c1e elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="459a5c1e" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-top-column elementor-element elementor-element-21f232d8" data-id="21f232d8" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-4a1fc360 elementor-widget elementor-widget-text-editor" data-id="4a1fc360" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>GARANTIA TOTAL DE SATISFAÇÃO</p>								</div>
				</div>
				<div class="elementor-element elementor-element-50c211d9 elementor-widget elementor-widget-heading" data-id="50c211d9" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"><span style="color:#FF0033">Experimente</span> por 7 Dias!</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-28d0ba25 elementor-widget elementor-widget-text-editor" data-id="28d0ba25" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>Não se preocupe, se o conteúdo descrito aqui não for o mesmo que você receber, você tem&nbsp;<strong>7 dias de garantia</strong>&nbsp;e nós devolvemos seu dinheiro sem burocracia!</p><p>Lembrando que seu acesso é vitalício .</p>								</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-top-column elementor-element elementor-element-1af22af5" data-id="1af22af5" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-373d52da elementor-widget elementor-widget-image" data-id="373d52da" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="500" height="305" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20500%20305'%3E%3C/svg%3E" class="attachment-full size-full wp-image-484" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/risco-zero-express.png 500w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/risco-zero-express-300x183.png 300w" data-lazy-sizes="(max-width: 500px) 100vw, 500px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/risco-zero-express.png"><noscript><img loading="lazy" decoding="async" width="500" height="305" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/risco-zero-express.png" class="attachment-full size-full wp-image-484" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/risco-zero-express.png 500w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/01/risco-zero-express-300x183.png 300w" sizes="(max-width: 500px) 100vw, 500px" /></noscript>															</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-11fab11e elementor-reverse-tablet elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="11fab11e" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-top-column elementor-element elementor-element-4545d9a7" data-id="4545d9a7" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-215ae088 elementor-widget elementor-widget-image" data-id="215ae088" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="400" height="400" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20400%20400'%3E%3C/svg%3E" class="attachment-full size-full wp-image-1162" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE.png 400w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE-150x150.png 150w" data-lazy-sizes="(max-width: 400px) 100vw, 400px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE.png"><noscript><img loading="lazy" decoding="async" width="400" height="400" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE.png" class="attachment-full size-full wp-image-1162" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE.png 400w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/HOJE-E-DIA-DE-150x150.png 150w" sizes="(max-width: 400px) 100vw, 400px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-top-column elementor-element elementor-element-2ca054fb" data-id="2ca054fb" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-5563c806 elementor-widget elementor-widget-heading" data-id="5563c806" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"><span style="color:#FF0033">Como Você Acessa</span> as suas planilhas + os bônus ?</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-62d94aff elementor-widget elementor-widget-text-editor" data-id="62d94aff" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p>Após realizar o seu pedido você irá receber um e-mail contendo todos os dados e informações para&nbsp;<em><strong>acessar a sua área restrita.</strong></em></p><p>Ao fazer o seu login você já pode baixar suas planilhas , vídeos e bônus.</p>								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-1e43b2ac elementor-reverse-tablet elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="1e43b2ac" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-160db53f" data-id="160db53f" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-1b274051 elementor-widget elementor-widget-heading" data-id="1b274051" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"><span style="color:#FF0033">Em dúvida sobre</span> comprar pela internet?</h2>				</div>
				</div>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-7506b367 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7506b367" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-33 elementor-inner-column elementor-element elementor-element-5009a91c" data-id="5009a91c" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-455d998d elementor-position-left elementor-vertical-align-middle elementor-view-stacked elementor-shape-circle elementor-mobile-position-top elementor-widget elementor-widget-icon-box" data-id="455d998d" data-element_type="widget" data-widget_type="icon-box.default">
				<div class="elementor-widget-container">
							<div class="elementor-icon-box-wrapper">

						<div class="elementor-icon-box-icon">
				<span class="elementor-icon elementor-animation-grow">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 402.08 402.09"><g id="Camada_2" data-name="Camada 2"><g id="Camada_1-2" data-name="Camada 1"><path d="M402.08,200.3v1.56a12,12,0,0,0-1.65,1.53c-9.85,13.53-19.73,27.05-29.46,40.68a8.05,8.05,0,0,0-1.19,5c1.56,16.4,3.19,32.8,5.06,49.17.32,2.86-.65,3.86-3,4.89-14.71,6.45-29.34,13.11-44.08,19.53a9.4,9.4,0,0,0-5.22,5.33c-6.38,14.61-13,29.11-19.38,43.71-1.09,2.47-2.12,3.5-5.16,3.15-16.24-1.88-32.51-3.5-48.79-5a9.78,9.78,0,0,0-5.69,1.54c-14.16,10.07-28.2,20.33-42.5,30.7l-17.79-12.87c-8.16-5.92-16.24-11.94-24.51-17.68a9.86,9.86,0,0,0-6-1.67q-24.42,2.24-48.79,5c-2.77.31-3.89-.46-5-2.88-6.49-14.84-13.06-29.65-19.83-44.37a11.12,11.12,0,0,0-4.68-4.68c-14.72-6.77-29.54-13.34-44.38-19.83-2.42-1.05-3.19-2.18-2.88-4.94q2.77-24.37,5-48.79a9.69,9.69,0,0,0-1.67-6c-10-14.06-20.2-28-30.53-42.22,1.81-2.53,3.61-5.07,5.43-7.58,8.45-11.66,17-23.26,25.27-35a9.76,9.76,0,0,0,1.52-5.66q-2.28-24.62-5-49.18c-.3-2.69.65-3.64,2.82-4.6C44.71,92.63,59.35,86,74.08,79.56a9.35,9.35,0,0,0,5.33-5.21C85.83,59.62,92.49,45,99,30.27c1-2.34,2-3.31,4.88-3,16.5,1.88,33,3.52,49.57,5.11a6.77,6.77,0,0,0,4.3-1c13.94-10,27.79-20.06,41.65-30.14A5.24,5.24,0,0,0,200.26,0h1.5A8.92,8.92,0,0,0,203,1.47c13.75,10,27.48,20,41.31,29.9a6.88,6.88,0,0,0,4.29,1c16.53-1.6,33-3.24,49.55-5.11,2.79-.32,3.87.51,4.92,2.91,6.49,14.83,13.05,29.63,19.82,44.34a11.06,11.06,0,0,0,4.68,4.68c14.71,6.77,29.51,13.33,44.35,19.82,2.39,1,3.23,2.12,2.91,4.92-1.86,16.36-3.5,32.75-5.05,49.14a8,8,0,0,0,1.21,5c9.72,13.62,19.59,27.13,29.45,40.65A11.38,11.38,0,0,0,402.08,200.3ZM285.51,347.84c5.81-13,11.61-25.69,17.17-38.51a11.07,11.07,0,0,1,6.24-6.36c12-5.13,23.88-10.61,35.85-15.85,2.11-.93,2.8-1.93,2.5-4.39-1.53-13-2.76-26-4.2-39a10.8,10.8,0,0,1,2.18-8.33c7.85-10.45,15.39-21.15,23.2-31.64,1.54-2.07,1.44-3.39-.06-5.42-7.87-10.6-15.68-21.26-23.25-32.08a11.7,11.7,0,0,1-2-7.11c1.16-13.15,2.62-26.28,4.2-39.39.31-2.56-.3-3.67-2.62-4.68q-18.69-8.14-37.2-16.66a8.59,8.59,0,0,1-3.9-3.89Q295.12,76,287,57.34c-1-2.26-2.07-3-4.68-2.65-13,1.54-26,2.73-39,4.21A10.83,10.83,0,0,1,235,56.56c-10.38-7.74-21-15.2-31.34-23-2.21-1.66-3.58-1.56-5.74,0Q182,45.47,165.83,56.88a11,11,0,0,1-6.39,1.86c-6-.31-12-1.2-17.94-1.83-8.43-.88-16.86-1.73-25.37-2.59-6,13.45-11.88,26.71-17.95,39.87A9.23,9.23,0,0,1,94,98.36c-12.33,5.7-24.75,11.21-37.19,16.68-2.1.92-2.82,1.91-2.53,4.37,1.57,13.11,2.81,26.26,4.32,39.38a10.36,10.36,0,0,1-2.22,7.93C48.6,177.21,41,187.89,33.24,198.38c-1.53,2.05-1.5,3.37,0,5.42,7.88,10.6,15.69,21.26,23.26,32.08a11.62,11.62,0,0,1,2,7.1c-1.16,13.15-2.61,26.28-4.19,39.39-.31,2.54.24,3.68,2.59,4.7,12.34,5.37,24.64,10.84,36.84,16.5A9.76,9.76,0,0,1,98.16,308c5.66,12.21,11.11,24.51,16.52,36.83,1,2.24,2,3,4.66,2.69,13-1.56,26-2.74,39-4.22a10.83,10.83,0,0,1,8.29,2.32c10.48,7.83,21.15,15.39,31.66,23.18,1.93,1.44,3.19,1.41,5.1,0,10.3-7.63,20.83-15,31-22.75,3.36-2.58,6.58-3,10.51-2.56C258.27,345,271.67,346.36,285.51,347.84Z"></path><path d="M299,172.25l24.08-7c13.82,41.45,3.12,103.55-48.91,140.15A127.54,127.54,0,0,1,89.41,139.18c31.11-55.61,90.81-72.38,133.51-63.52-1.41,8-2.82,16.12-4.27,24.45-38.57-4.77-71.39,6.16-96.46,36.22C103.9,158.25,96.37,184,99.68,212.42a101.61,101.61,0,0,0,113.37,89.71c31.06-3.86,55.74-18.95,73-45.11C303.21,231,307.06,202.6,299,172.25Z"></path><path d="M260,172,175.3,256.72,129,210.39l17.41-17.46,28.49,28.56,67.35-67.32Z"></path><path d="M250.39,82.75l24.83,13.89L260.3,117.55l-19.85-11.07Z"></path><path d="M277.25,132.81l19.15-17.15c5.56,7.73,10.92,15.18,16.54,23l-22.43,12.61Z"></path></g></g></svg>				</span>
			</div>
			
						<div class="elementor-icon-box-content">

				
									<p class="elementor-icon-box-description">
						
Dados pessoais seguros e não são compartilhados.					</p>
				
			</div>
			
		</div>
						</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-33 elementor-inner-column elementor-element elementor-element-1165d297" data-id="1165d297" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-2445e5c4 elementor-position-left elementor-vertical-align-middle elementor-view-stacked elementor-shape-circle elementor-mobile-position-top elementor-widget elementor-widget-icon-box" data-id="2445e5c4" data-element_type="widget" data-widget_type="icon-box.default">
				<div class="elementor-widget-container">
							<div class="elementor-icon-box-wrapper">

						<div class="elementor-icon-box-icon">
				<span class="elementor-icon elementor-animation-grow">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 131.34 131.41"><g id="Camada_2" data-name="Camada 2"><g id="Camada_1-2" data-name="Camada 1"><path d="M0,94.72V21.34A18.34,18.34,0,0,1,5.88,11.25a36.77,36.77,0,0,1,13-7.32A75,75,0,0,1,60.16,2,43.14,43.14,0,0,1,78,10c4.78,3.81,7.44,8.58,7.24,14.93-.21,6.83,0,13.67,0,20.51v1.44a42.32,42.32,0,0,1,15.21,82.91c-2.71.73-5.52,1.07-8.28,1.59H86a6.64,6.64,0,0,0-1-.23,39.5,39.5,0,0,1-11.29-2.68,42.44,42.44,0,0,1-17.51-12.75,1.83,1.83,0,0,0-1.33-.63c-2.47.18-4.92.57-7.39.72-10.53.63-20.84-.5-30.65-4.51C9,108.14,2.06,103.84,0,94.72ZM89.09,54.44a34.64,34.64,0,1,0,34.59,34.75A34.69,34.69,0,0,0,89.09,54.44ZM43.48,7.73a67.48,67.48,0,0,0-20.24,2.85c-4.76,1.5-9.32,3.44-12.89,7.08s-3.51,7.29,0,10.93a5.85,5.85,0,0,0,1.12,1.05C13.94,31.17,16.32,33,19,34.09c14.14,5.56,28.56,5.84,43.1,1.67a28.06,28.06,0,0,0,12.66-7c3.62-3.68,3.6-7.57,0-11.28a23.56,23.56,0,0,0-7.17-4.88C59.82,9,51.48,7.85,43.48,7.73ZM7.7,36.67c0,3,.13,5.77,0,8.54a9.3,9.3,0,0,0,3.64,7.93,27.87,27.87,0,0,0,9,5.12C31.78,62.48,43.59,63,55.61,61a6.41,6.41,0,0,0,3.69-2A41.91,41.91,0,0,1,76.45,48.63c.4-.13,1-.55,1-.85.07-3.61,0-7.23,0-11C66.87,44,55,46.22,42.67,46.19S18.4,43.88,7.7,36.67Zm0,23.65c0,3,0,5.94,0,8.84A7.8,7.8,0,0,0,9.5,74.35a19.63,19.63,0,0,0,6.76,5.2c9.39,4.69,19.44,5.9,29.77,5.63.74,0,.9-.35,1-1a42,42,0,0,1,4.13-13.93,4.63,4.63,0,0,0,.25-.77C36,70.59,21.17,69.11,7.7,60.32ZM46.86,92.85a80.71,80.71,0,0,1-20.4-1.65A49.92,49.92,0,0,1,7.7,83.29c0,2.93.12,5.61,0,8.28a8.37,8.37,0,0,0,3.42,7.49,37.1,37.1,0,0,0,7.35,4.57c9.14,4,18.81,5.07,28.7,4.55,1.28-.07,2.54-.21,4-.33A43.69,43.69,0,0,1,46.86,92.85Z"></path><path d="M92.89,115.91h-7.7c0-2.36,0-4.65,0-7a1.65,1.65,0,0,0-1.12-1.81c-4.2-2.07-6.32-5.54-6.64-10.29h7.67c0,.2.08.44.14.67a3.85,3.85,0,0,0,7.61-1,3.86,3.86,0,0,0-3.95-3.59,11.68,11.68,0,0,1-6.59-2.18A11.5,11.5,0,0,1,84.1,71a1.62,1.62,0,0,0,1.12-1.8c-.08-2.3,0-4.6,0-7h7.7c0,1.73.11,3.52,0,5.28-.14,1.91.21,3.12,2.2,4.16,3.66,1.92,5.32,5.37,5.55,9.6H93c0-.18-.08-.38-.13-.58a3.85,3.85,0,1,0-3.63,4.56,11.32,11.32,0,0,1,8.88,4.41,11.48,11.48,0,0,1-4.15,17.55,1.55,1.55,0,0,0-1.07,1.7C92.93,111.2,92.89,113.5,92.89,115.91Z"></path></g></g></svg>				</span>
			</div>
			
						<div class="elementor-icon-box-content">

				
									<p class="elementor-icon-box-description">
						Pagamento automático, rápido e seguro.					</p>
				
			</div>
			
		</div>
						</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-33 elementor-inner-column elementor-element elementor-element-6a6a27f" data-id="6a6a27f" data-element_type="column" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-1fc455e7 elementor-position-left elementor-vertical-align-middle elementor-view-stacked elementor-shape-circle elementor-mobile-position-top elementor-widget elementor-widget-icon-box" data-id="1fc455e7" data-element_type="widget" data-widget_type="icon-box.default">
				<div class="elementor-widget-container">
							<div class="elementor-icon-box-wrapper">

						<div class="elementor-icon-box-icon">
				<span class="elementor-icon elementor-animation-grow">
				<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" id="Capa_1" x="0px" y="0px" viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve"><g>	<g>		<path d="M256,60c-57.897,0-105,47.103-105,105c0,35.943,18.126,69.015,48.487,88.467c31.003,19.863,69.06,21.974,104.426,5.703    c7.525-3.462,10.82-12.37,7.357-19.896c-3.462-7.525-12.369-10.82-19.896-7.358c-25.86,11.898-53.454,10.545-75.703-3.709    C193.961,214.298,181,190.669,181,165c0-41.355,33.645-75,75-75s75,33.645,75,75c0,8.271-6.729,15-15,15    c-7.558,0-14.618-5.732-14.998-14.772C301.001,165.152,301,165.076,301,165c0-24.813-20.187-45-45-45s-45,20.187-45,45    s20.187,45,45,45c11.516,0,22.031-4.353,29.999-11.494C293.966,205.648,304.483,210,316,210c24.813,0,45-20.187,45-45    C361,107.103,313.897,60,256,60z M270.789,167.406C269.631,174.535,263.45,180,256,180c-8.271,0-15-6.729-15-15s6.729-15,15-15    c7.691,0,14.04,5.82,14.895,13.285C270.671,164.648,270.634,166.035,270.789,167.406z"></path>	</g></g><g>	<g>		<path d="M480.999,196.976c-0.004-3.879-1.566-7.756-4.393-10.583L421,130.787V15c0-8.284-6.716-15-15-15H106    c-8.284,0-15,6.716-15,15v115.787l-55.606,55.606c-0.052,0.052-0.096,0.11-0.147,0.163c-2.811,2.896-4.24,6.709-4.246,10.42    c0,0.01-0.001,0.019-0.001,0.029V467c0,24.845,20.216,45,45,45h360c24.839,0,45-20.207,45-45V197.005    C481,196.995,480.999,196.986,480.999,196.976z M421,173.213L444.787,197L421,220.787V173.213z M121,137.005    c0-0.003,0-0.007,0-0.01V30h270v106.995c0,0.003,0,0.007,0,0.01v113.782L309.787,332H202.213L121,250.787V137.005z M91,173.213    v47.574L67.213,197L91,173.213z M61,460.787V233.213L174.787,347L61,460.787z M82.214,482l119.999-120h107.574l119.999,120H82.214    z M451,460.787L337.213,347L451,233.213V460.787z"></path>	</g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g></svg>				</span>
			</div>
			
						<div class="elementor-icon-box-content">

				
									<p class="elementor-icon-box-description">
						Acesso enviado para seu email Imediatamente.					</p>
				
			</div>
			
		</div>
						</div>
				</div>
					</div>
		</div>
					</div>
		</section>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-18f28bca elementor-reverse-tablet elementor-reverse-mobile elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="18f28bca" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2e2fa511" data-id="2e2fa511" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-73a0adc0 elementor-widget elementor-widget-menu-anchor" data-id="73a0adc0" data-element_type="widget" data-widget_type="menu-anchor.default">
				<div class="elementor-widget-container">
							<div class="elementor-menu-anchor" id="PRECO"></div>
						</div>
				</div>
				<div class="elementor-element elementor-element-56b5d010 elementor-widget elementor-widget-menu-anchor" data-id="56b5d010" data-element_type="widget" data-widget_type="menu-anchor.default">
				<div class="elementor-widget-container">
							<div class="elementor-menu-anchor" id="oferta"></div>
						</div>
				</div>
				<div class="elementor-element elementor-element-54d66670 elementor-widget elementor-widget-heading" data-id="54d66670" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"><span style="color:#FF0033">Oferta Especial</span> Por Tempo Limitado!</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-60a76013 elementor-widget elementor-widget-heading" data-id="60a76013" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">de <s>R$ 97,00</s> Por Apenas</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-4b65f477 elementor-widget elementor-widget-heading" data-id="4b65f477" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">2x de <span style="background-color:#FF0033;color:#fff">R$ 19,81*</span></h2>				</div>
				</div>
				<div class="elementor-element elementor-element-5637a987 elementor-widget elementor-widget-heading" data-id="5637a987" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">ou à vista por R$ 37,90</h2>				</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-5772beb8 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="5772beb8" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-6066ee3" data-id="6066ee3" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-587c5e36 elementor-align-center elementor-mobile-align-center elementor-tablet-align-center elementor-widget elementor-widget-button" data-id="587c5e36" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
									<div class="elementor-button-wrapper">
					<a class="elementor-button elementor-button-link elementor-size-sm elementor-animation-grow" href="https://pay.kiwify.com.br/42jap0q?afid=QpVn94hI">
						<span class="elementor-button-content-wrapper">
									<span class="elementor-button-text">sim, QUERO TREINAR DE VERDADE !</span>
					</span>
					</a>
				</div>
								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-156011e6 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="156011e6" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4618d21e" data-id="4618d21e" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-39cb384 elementor-widget elementor-widget-heading" data-id="39cb384" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">NÃO LEU TUDO ? VOU RESUMIR PARA VOCÊ.<br>
<div><br></div></h2>				</div>
				</div>
				<div class="elementor-element elementor-element-fe44bc9 elementor-widget elementor-widget-heading" data-id="fe44bc9" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">Se você não quer mais ficar horas e horas procurando como treinar ou está cansado de pagar caro para um personal . </h2>				</div>
				</div>
				<div class="elementor-element elementor-element-25f1714 elementor-widget elementor-widget-heading" data-id="25f1714" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">Então adquirir as PLANILHAS DE TREINO e o PLANO ALIMENTAR + OS BÔNUS é uma decisão inteligente . <br><br>Você terá acesso a metodologia usada por PERSONAIS para aumentar os resultados de forma rápida e eficaz.<br><br><br></h2>				</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-377a77aa elementor-reverse-tablet elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="377a77aa" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-50 elementor-top-column elementor-element elementor-element-55f6cd77" data-id="55f6cd77" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-44c3740c elementor-widget elementor-widget-image" data-id="44c3740c" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
															<img decoding="async" width="1080" height="1080" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201080%201080'%3E%3C/svg%3E" class="attachment-full size-full wp-image-844" alt="" data-lazy-srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-768x768.png 768w" data-lazy-sizes="(max-width: 1080px) 100vw, 1080px" data-lazy-src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada.png"><noscript><img loading="lazy" decoding="async" width="1080" height="1080" src="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada.png" class="attachment-full size-full wp-image-844" alt="" srcset="https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada.png 1080w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-300x300.png 300w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-1024x1024.png 1024w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-150x150.png 150w, https://treinamentoonlinerdc.com.br/wp-content/uploads/2024/02/planilhas-personalizada-768x768.png 768w" sizes="(max-width: 1080px) 100vw, 1080px" /></noscript>															</div>
				</div>
					</div>
		</div>
				<div class="elementor-column elementor-col-50 elementor-top-column elementor-element elementor-element-42fe511a" data-id="42fe511a" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-1dd0a76 elementor-widget elementor-widget-heading" data-id="1dd0a76" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"><span style="color:#FF0033">você vai ter acesso </span> a tudo isso com 85% de desconto .</h2>				</div>
				</div>
				<div class="elementor-element elementor-element-22d0d19 elementor-icon-list--layout-traditional elementor-list-item-link-full_width elementor-widget elementor-widget-icon-list" data-id="22d0d19" data-element_type="widget" data-widget_type="icon-list.default">
				<div class="elementor-widget-container">
							<ul class="elementor-icon-list-items">
							<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-arrow-alt-circle-right" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zM140 300h116v70.9c0 10.7 13 16.1 20.5 8.5l114.3-114.9c4.7-4.7 4.7-12.2 0-16.9l-114.3-115c-7.6-7.6-20.5-2.2-20.5 8.5V212H140c-6.6 0-12 5.4-12 12v64c0 6.6 5.4 12 12 12z"></path></svg>						</span>
										<span class="elementor-icon-list-text">+ DE 30 PLANILHAS PERSONALIZADAS TREINO COMPLETO.</span>
									</li>
								<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-arrow-alt-circle-right" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zM140 300h116v70.9c0 10.7 13 16.1 20.5 8.5l114.3-114.9c4.7-4.7 4.7-12.2 0-16.9l-114.3-115c-7.6-7.6-20.5-2.2-20.5 8.5V212H140c-6.6 0-12 5.4-12 12v64c0 6.6 5.4 12 12 12z"></path></svg>						</span>
										<span class="elementor-icon-list-text">250 RECEITAS METABOLICAS.</span>
									</li>
								<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-arrow-alt-circle-right" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zM140 300h116v70.9c0 10.7 13 16.1 20.5 8.5l114.3-114.9c4.7-4.7 4.7-12.2 0-16.9l-114.3-115c-7.6-7.6-20.5-2.2-20.5 8.5V212H140c-6.6 0-12 5.4-12 12v64c0 6.6 5.4 12 12 12z"></path></svg>						</span>
										<span class="elementor-icon-list-text">DESAFIO 24 DIAS.</span>
									</li>
						</ul>
						</div>
				</div>
				<div class="elementor-element elementor-element-eefbca1 elementor-icon-list--layout-traditional elementor-list-item-link-full_width elementor-widget elementor-widget-icon-list" data-id="eefbca1" data-element_type="widget" data-widget_type="icon-list.default">
				<div class="elementor-widget-container">
							<ul class="elementor-icon-list-items">
							<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-arrow-alt-circle-right" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zM140 300h116v70.9c0 10.7 13 16.1 20.5 8.5l114.3-114.9c4.7-4.7 4.7-12.2 0-16.9l-114.3-115c-7.6-7.6-20.5-2.2-20.5 8.5V212H140c-6.6 0-12 5.4-12 12v64c0 6.6 5.4 12 12 12z"></path></svg>						</span>
										<span class="elementor-icon-list-text">TREINO FUNCIONAL.</span>
									</li>
								<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-arrow-alt-circle-right" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zM140 300h116v70.9c0 10.7 13 16.1 20.5 8.5l114.3-114.9c4.7-4.7 4.7-12.2 0-16.9l-114.3-115c-7.6-7.6-20.5-2.2-20.5 8.5V212H140c-6.6 0-12 5.4-12 12v64c0 6.6 5.4 12 12 12z"></path></svg>						</span>
										<span class="elementor-icon-list-text">TREINO EM VÍDEO DE CADA EXERCÍCIO.</span>
									</li>
								<li class="elementor-icon-list-item">
											<span class="elementor-icon-list-icon">
							<svg aria-hidden="true" class="e-font-icon-svg e-fas-arrow-alt-circle-right" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zM140 300h116v70.9c0 10.7 13 16.1 20.5 8.5l114.3-114.9c4.7-4.7 4.7-12.2 0-16.9l-114.3-115c-7.6-7.6-20.5-2.2-20.5 8.5V212H140c-6.6 0-12 5.4-12 12v64c0 6.6 5.4 12 12 12z"></path></svg>						</span>
										<span class="elementor-icon-list-text">+ 3 BÔNUS EXCLUSIVO E UM PRESENTE SUPRESA.</span>
									</li>
						</ul>
						</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-6c0b4519 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="6c0b4519" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-5754e143" data-id="5754e143" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-2e91b508 elementor-align-center elementor-mobile-align-center elementor-tablet-align-center elementor-widget elementor-widget-button" data-id="2e91b508" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
									<div class="elementor-button-wrapper">
					<a class="elementor-button elementor-button-link elementor-size-sm elementor-animation-grow" href="https://pay.kiwify.com.br/42jap0q?afid=QpVn94hI">
						<span class="elementor-button-content-wrapper">
									<span class="elementor-button-text">sim, QUERO TREINAR DE VERDADE !</span>
					</span>
					</a>
				</div>
								</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-5724d475 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="5724d475" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-6276f2ec" data-id="6276f2ec" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-6b5065d1 elementor-widget elementor-widget-heading" data-id="6b5065d1" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default"><span style="font-weight:normal"><p dir="ltr" style="line-height:1.38;margin-top:0pt;margin-bottom:0pt"><br></p></span>DÚVIDAS MAIS COMUNS :</h2>				</div>
				</div>
				<section class="elementor-section elementor-inner-section elementor-element elementor-element-2bbb92aa elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="2bbb92aa" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-inner-column elementor-element elementor-element-61c7ef2" data-id="61c7ef2" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-e1909f elementor-widget elementor-widget-toggle" data-id="e1909f" data-element_type="widget" data-widget_type="toggle.default">
				<div class="elementor-widget-container">
							<div class="elementor-toggle">
							<div class="elementor-toggle-item">
					<div id="elementor-tab-title-1471" class="elementor-tab-title" data-tab="1" role="button" aria-controls="elementor-tab-content-1471" aria-expanded="false">
												<span class="elementor-toggle-icon elementor-toggle-icon-right" aria-hidden="true">
															<span class="elementor-toggle-icon-closed"><svg class="e-font-icon-svg e-fas-caret-right" viewBox="0 0 192 512" xmlns="http://www.w3.org/2000/svg"><path d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path></svg></span>
								<span class="elementor-toggle-icon-opened"><svg class="elementor-toggle-icon-opened e-font-icon-svg e-fas-caret-up" viewBox="0 0 320 512" xmlns="http://www.w3.org/2000/svg"><path d="M288.662 352H31.338c-17.818 0-26.741-21.543-14.142-34.142l128.662-128.662c7.81-7.81 20.474-7.81 28.284 0l128.662 128.662c12.6 12.599 3.676 34.142-14.142 34.142z"></path></svg></span>
													</span>
												<a class="elementor-toggle-title" tabindex="0">O que vou receber ?</a>
					</div>

					<div id="elementor-tab-content-1471" class="elementor-tab-content elementor-clearfix" data-tab="1" role="region" aria-labelledby="elementor-tab-title-1471"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="color: #1b1a39; font-family: Arial, sans-serif;"><span style="font-size: 15.3333px; white-space-collapse: preserve; background-color: #f6f6f6;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Você vai ter acesso a mais de 30 planilhas de treino personalizadas e mais de 100 vídeos de como executar cada exercício e os bônus especiais. Mais um presente ESPECIAL!</span></span></span></span></p></div>
				</div>
							<div class="elementor-toggle-item">
					<div id="elementor-tab-title-1472" class="elementor-tab-title" data-tab="2" role="button" aria-controls="elementor-tab-content-1472" aria-expanded="false">
												<span class="elementor-toggle-icon elementor-toggle-icon-right" aria-hidden="true">
															<span class="elementor-toggle-icon-closed"><svg class="e-font-icon-svg e-fas-caret-right" viewBox="0 0 192 512" xmlns="http://www.w3.org/2000/svg"><path d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path></svg></span>
								<span class="elementor-toggle-icon-opened"><svg class="elementor-toggle-icon-opened e-font-icon-svg e-fas-caret-up" viewBox="0 0 320 512" xmlns="http://www.w3.org/2000/svg"><path d="M288.662 352H31.338c-17.818 0-26.741-21.543-14.142-34.142l128.662-128.662c7.81-7.81 20.474-7.81 28.284 0l128.662 128.662c12.6 12.599 3.676 34.142-14.142 34.142z"></path></svg></span>
													</span>
												<a class="elementor-toggle-title" tabindex="0">Para quem é indicado ?</a>
					</div>

					<div id="elementor-tab-content-1472" class="elementor-tab-content elementor-clearfix" data-tab="2" role="region" aria-labelledby="elementor-tab-title-1472"><p><b><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Para alunos iniciantes, personal trainer e alunos avançados.&nbsp;</span></span></b></p></div>
				</div>
							<div class="elementor-toggle-item">
					<div id="elementor-tab-title-1473" class="elementor-tab-title" data-tab="3" role="button" aria-controls="elementor-tab-content-1473" aria-expanded="false">
												<span class="elementor-toggle-icon elementor-toggle-icon-right" aria-hidden="true">
															<span class="elementor-toggle-icon-closed"><svg class="e-font-icon-svg e-fas-caret-right" viewBox="0 0 192 512" xmlns="http://www.w3.org/2000/svg"><path d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path></svg></span>
								<span class="elementor-toggle-icon-opened"><svg class="elementor-toggle-icon-opened e-font-icon-svg e-fas-caret-up" viewBox="0 0 320 512" xmlns="http://www.w3.org/2000/svg"><path d="M288.662 352H31.338c-17.818 0-26.741-21.543-14.142-34.142l128.662-128.662c7.81-7.81 20.474-7.81 28.284 0l128.662 128.662c12.6 12.599 3.676 34.142-14.142 34.142z"></path></svg></span>
													</span>
												<a class="elementor-toggle-title" tabindex="0">Quais são as formas de pagamentos? É seguro?</a>
					</div>

					<div id="elementor-tab-content-1473" class="elementor-tab-content elementor-clearfix" data-tab="3" role="region" aria-labelledby="elementor-tab-title-1473"><p><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Trabalhamos com as principais formas de pagamentos do mercado e com um site </span></span></span></span><strong><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">super seguro</span></span></span></span></strong><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"> com criptografia de ponta.</span></span></span></span></p></div>
				</div>
							<div class="elementor-toggle-item">
					<div id="elementor-tab-title-1474" class="elementor-tab-title" data-tab="4" role="button" aria-controls="elementor-tab-content-1474" aria-expanded="false">
												<span class="elementor-toggle-icon elementor-toggle-icon-right" aria-hidden="true">
															<span class="elementor-toggle-icon-closed"><svg class="e-font-icon-svg e-fas-caret-right" viewBox="0 0 192 512" xmlns="http://www.w3.org/2000/svg"><path d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path></svg></span>
								<span class="elementor-toggle-icon-opened"><svg class="elementor-toggle-icon-opened e-font-icon-svg e-fas-caret-up" viewBox="0 0 320 512" xmlns="http://www.w3.org/2000/svg"><path d="M288.662 352H31.338c-17.818 0-26.741-21.543-14.142-34.142l128.662-128.662c7.81-7.81 20.474-7.81 28.284 0l128.662 128.662c12.6 12.599 3.676 34.142-14.142 34.142z"></path></svg></span>
													</span>
												<a class="elementor-toggle-title" tabindex="0">Por quanto tempo terei acesso ao conteúdo?</a>
					</div>

					<div id="elementor-tab-content-1474" class="elementor-tab-content elementor-clearfix" data-tab="4" role="region" aria-labelledby="elementor-tab-title-1474"><p><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">Comprando HOJE você terá </span></span></span></span><strong><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;">acesso vitalício</span></span></span></span></strong><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"><span style="vertical-align: inherit;"> a todo o conteúdo proposto.</span></span></span></span></p></div>
				</div>
								</div>
						</div>
				</div>
					</div>
		</div>
					</div>
		</section>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-1dd407ae elementor-section-content-middle elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="1dd407ae" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-no">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-6d2d293d" data-id="6d2d293d" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-75c567fe elementor-widget elementor-widget-heading" data-id="75c567fe" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
					<h2 class="elementor-heading-title elementor-size-default">Método Treino Perfeito  - Todos os direitos Reservados.</h2>				</div>
				</div>
					</div>
		</div>
					</div>
		</section>
		<div class="elementor-element elementor-element-598dcb7 e-flex e-con-boxed e-con e-parent" data-id="598dcb7" data-element_type="container">
					<div class="e-con-inner">
				<div class="elementor-element elementor-element-06efcd8 elementor-widget elementor-widget-html" data-id="06efcd8" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
					<!-- Meta Pixel Code -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '1050066996448280');
fbq('track', 'PageView');
</script>
<noscript><img loading="lazy" height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=1050066996448280&ev=PageView&noscript=1"
/></noscript>
<!-- End Meta Pixel Code -->				</div>
				</div>
					</div>
				</div>
				</div>
		<input type="hidden" value="https://treinamentoonlinerdc.com.br/updateAutomaticMetrics" id="splUrlAutomaticLinks"><input type="hidden" value="836" id="splPostIdAutomaticLinks">			<script type="text/javascript">
				const lazyloadRunObserver = () => {
					const lazyloadBackgrounds = document.querySelectorAll( `.e-con.e-parent:not(.e-lazyloaded)` );
					const lazyloadBackgroundObserver = new IntersectionObserver( ( entries ) => {
						entries.forEach( ( entry ) => {
							if ( entry.isIntersecting ) {
								let lazyloadBackground = entry.target;
								if( lazyloadBackground ) {
									lazyloadBackground.classList.add( 'e-lazyloaded' );
								}
								lazyloadBackgroundObserver.unobserve( entry.target );
							}
						});
					}, { rootMargin: '200px 0px 200px 0px' } );
					lazyloadBackgrounds.forEach( ( lazyloadBackground ) => {
						lazyloadBackgroundObserver.observe( lazyloadBackground );
					} );
				};
				const events = [
					'DOMContentLoaded',
					'elementor/lazyload/observe',
				];
				events.forEach( ( event ) => {
					document.addEventListener( event, lazyloadRunObserver );
				} );
			</script>
			<noscript><img height="1" width="1" style="display: none;" src="https://www.facebook.com/tr?id=908259174143698&ev=PageView&noscript=1&cd%5Bpage_title%5D=PLANILHAS+PERSONALIZADAS&cd%5Bpost_type%5D=page&cd%5Bpost_id%5D=836&cd%5Bplugin%5D=PixelYourSite&cd%5Buser_role%5D=guest&cd%5Bevent_url%5D=treinamentoonlinerdc.com.br%2Fplanilhas-personalizadas%2F" alt=""></noscript>
<script data-minify="1" src="https://treinamentoonlinerdc.com.br/wp-content/cache/min/1/wp-content/plugins/super-links/assets/js/automatic-links.js?ver=1730199689" id="spl_automaticLink_js-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/themes/hello-elementor/assets/js/hello-frontend.min.js?ver=3.2.1" id="hello-theme-frontend-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/js/webpack.runtime.min.js?ver=3.26.4" id="elementor-webpack-runtime-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/js/frontend-modules.min.js?ver=3.26.4" id="elementor-frontend-modules-js"></script>
<script src="https://treinamentoonlinerdc.com.br/wp-includes/js/jquery/ui/core.min.js?ver=1.13.3" id="jquery-ui-core-js"></script>
<script id="elementor-frontend-js-before">
var elementorFrontendConfig = {"environmentMode":{"edit":false,"wpPreview":false,"isScriptDebug":false},"i18n":{"shareOnFacebook":"Share on Facebook","shareOnTwitter":"Share on Twitter","pinIt":"Pin it","download":"Download","downloadImage":"Download image","fullscreen":"Fullscreen","zoom":"Zoom","share":"Share","playVideo":"Play Video","previous":"Previous","next":"Next","close":"Close","a11yCarouselPrevSlideMessage":"Previous slide","a11yCarouselNextSlideMessage":"Next slide","a11yCarouselFirstSlideMessage":"This is the first slide","a11yCarouselLastSlideMessage":"This is the last slide","a11yCarouselPaginationBulletMessage":"Go to slide"},"is_rtl":false,"breakpoints":{"xs":0,"sm":480,"md":768,"lg":1025,"xl":1440,"xxl":1600},"responsive":{"breakpoints":{"mobile":{"label":"Mobile Portrait","value":767,"default_value":767,"direction":"max","is_enabled":true},"mobile_extra":{"label":"Mobile Landscape","value":880,"default_value":880,"direction":"max","is_enabled":false},"tablet":{"label":"Tablet Portrait","value":1024,"default_value":1024,"direction":"max","is_enabled":true},"tablet_extra":{"label":"Tablet Landscape","value":1200,"default_value":1200,"direction":"max","is_enabled":false},"laptop":{"label":"Laptop","value":1366,"default_value":1366,"direction":"max","is_enabled":false},"widescreen":{"label":"Widescreen","value":2400,"default_value":2400,"direction":"min","is_enabled":false}},
"hasCustomBreakpoints":false},"version":"3.26.4","is_static":false,"experimentalFeatures":{"e_font_icon_svg":true,"additional_custom_breakpoints":true,"container":true,"e_swiper_latest":true,"e_nested_atomic_repeaters":true,"e_onboarding":true,"e_css_smooth_scroll":true,"hello-theme-header-footer":true,"home_screen":true,"landing-pages":true,"nested-elements":true,"editor_v2":true,"link-in-bio":true,"floating-buttons":true},"urls":{"assets":"https:\/\/treinamentoonlinerdc.com.br\/wp-content\/plugins\/elementor\/assets\/","ajaxurl":"https:\/\/treinamentoonlinerdc.com.br\/wp-admin\/admin-ajax.php","uploadUrl":"http:\/\/treinamentoonlinerdc.com.br\/wp-content\/uploads"},"nonces":{"floatingButtonsClickTracking":"ea1d382b93"},"swiperClass":"swiper","settings":{"page":[],"editorPreferences":[]},"kit":{"active_breakpoints":["viewport_mobile","viewport_tablet"],"global_image_lightbox":"yes","lightbox_enable_counter":"yes","lightbox_enable_fullscreen":"yes","lightbox_enable_zoom":"yes","lightbox_enable_share":"yes","lightbox_title_src":"title","lightbox_description_src":"description","hello_header_logo_type":"title","hello_footer_logo_type":"logo"},"post":{"id":836,"title":"PLANILHAS%20PERSONALIZADAS%20%E2%80%93%20Curso0nline","excerpt":"","featuredImage":false}};
</script>
<script src="https://treinamentoonlinerdc.com.br/wp-content/plugins/elementor/assets/js/frontend.min.js?ver=3.26.4" id="elementor-frontend-js"></script>
<script>window.lazyLoadOptions=[{elements_selector:"img[data-lazy-src],.rocket-lazyload,iframe[data-lazy-src]",data_src:"lazy-src",data_srcset:"lazy-srcset",data_sizes:"lazy-sizes",class_loading:"lazyloading",class_loaded:"lazyloaded",threshold:300,callback_loaded:function(element){if(element.tagName==="IFRAME"&&element.dataset.rocketLazyload=="fitvidscompatible"){if(element.classList.contains("lazyloaded")){if(typeof window.jQuery!="undefined"){if(jQuery.fn.fitVids){jQuery(element).parent().fitVids()}}}}}},{elements_selector:".rocket-lazyload",data_src:"lazy-src",data_srcset:"lazy-srcset",data_sizes:"lazy-sizes",class_loading:"lazyloading",class_loaded:"lazyloaded",threshold:300,}];window.addEventListener('LazyLoad::Initialized',function(e){var lazyLoadInstance=e.detail.instance;if(window.MutationObserver){var observer=new MutationObserver(function(mutations){var image_count=0;var iframe_count=0;var rocketlazy_count=0;mutations.forEach(function(mutation){for(var i=0;i<mutation.addedNodes.length;i++){if(typeof mutation.addedNodes[i].getElementsByTagName!=='function'){continue}
if(typeof mutation.addedNodes[i].getElementsByClassName!=='function'){continue}
images=mutation.addedNodes[i].getElementsByTagName('img');is_image=mutation.addedNodes[i].tagName=="IMG";iframes=mutation.addedNodes[i].getElementsByTagName('iframe');is_iframe=mutation.addedNodes[i].tagName=="IFRAME";rocket_lazy=mutation.addedNodes[i].getElementsByClassName('rocket-lazyload');image_count+=images.length;iframe_count+=iframes.length;rocketlazy_count+=rocket_lazy.length;if(is_image){image_count+=1}
if(is_iframe){iframe_count+=1}}});if(image_count>0||iframe_count>0||rocketlazy_count>0){lazyLoadInstance.update()}});var b=document.getElementsByTagName("body")[0];var config={childList:!0,subtree:!0};observer.observe(b,config)}},!1)</script><script data-no-minify="1" async="" src="https://treinamentoonlinerdc.com.br/wp-content/plugins/wp-rocket/assets/js/lazyload/17.5/lazyload.min.js"></script><script>function lazyLoadThumb(e){var t='<img data-lazy-src="https://i.ytimg.com/vi/ID/hqdefault.jpg" alt="" width="480" height="360"><noscript><img src="https://i.ytimg.com/vi/ID/hqdefault.jpg" alt="" width="480" height="360"></noscript>',a='<button class="play" aria-label="play Youtube video"></button>';return t.replace("ID",e)+a}function lazyLoadYoutubeIframe(){var e=document.createElement("iframe"),t="ID?autoplay=1";t+=0===this.parentNode.dataset.query.length?'':'&'+this.parentNode.dataset.query;e.setAttribute("src",t.replace("ID",this.parentNode.dataset.src)),e.setAttribute("frameborder","0"),e.setAttribute("allowfullscreen","1"),e.setAttribute("allow", "accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"),this.parentNode.parentNode.replaceChild(e,this.parentNode)}document.addEventListener("DOMContentLoaded",function(){var e,t,p,a=document.getElementsByClassName("rll-youtube-player");for(t=0;t<a.length;t++)e=document.createElement("div"),e.setAttribute("data-id",a[t].dataset.id),e.setAttribute("data-query", a[t].dataset.query),e.setAttribute("data-src", a[t].dataset.src),e.innerHTML=lazyLoadThumb(a[t].dataset.id),a[t].appendChild(e),p=e.querySelector('.play'),p.onclick=lazyLoadYoutubeIframe});</script>	<script>class RocketElementorAnimation{constructor(){this.deviceMode=document.createElement("span"),this.deviceMode.id="elementor-device-mode",this.deviceMode.setAttribute("class","elementor-screen-only"),document.body.appendChild(this.deviceMode)}_detectAnimations(){let t=getComputedStyle(this.deviceMode,":after").content.replace(/"/g,"");this.animationSettingKeys=this._listAnimationSettingsKeys(t),document.querySelectorAll(".elementor-invisible[data-settings]").forEach(t=>{const e=t.getBoundingClientRect();if(e.bottom>=0&&e.top<=window.innerHeight)try{this._animateElement(t)}catch(t){}})}_animateElement(t){const e=JSON.parse(t.dataset.settings),i=e._animation_delay||e.animation_delay||0,n=e[this.animationSettingKeys.find(t=>e[t])];if("none"===n)return void t.classList.remove("elementor-invisible");t.classList.remove(n),this.currentAnimation&&t.classList.remove(this.currentAnimation),this.currentAnimation=n;let s=setTimeout(()=>{t.classList.remove("elementor-invisible"),t.classList.add("animated",n),this._removeAnimationSettings(t,e)},i);window.addEventListener("rocket-startLoading",function(){clearTimeout(s)})}_listAnimationSettingsKeys(t="mobile"){const e=[""];switch(t){case"mobile":e.unshift("_mobile");case"tablet":e.unshift("_tablet");case"desktop":e.unshift("_desktop")}const i=[];return["animation","_animation"].forEach(t=>{e.forEach(e=>{i.push(t+e)})}),i}_removeAnimationSettings(t,e){this._listAnimationSettingsKeys().forEach(t=>delete e[t]),t.dataset.settings=JSON.stringify(e)}static run(){const t=new RocketElementorAnimation;requestAnimationFrame(t._detectAnimations.bind(t))}}document.addEventListener("DOMContentLoaded",RocketElementorAnimation.run);</script> <script type="text/javascript" id="perfmatters-delayed-styles-js">!function(){const e=["keydown","mousemove","wheel","touchmove","touchstart","touchend"];function t(){document.querySelectorAll("link[data-pmdelayedstyle]").forEach(function(e){e.setAttribute("href",e.getAttribute("data-pmdelayedstyle"))}),e.forEach(function(e){window.removeEventListener(e,t,{passive:!0})})}e.forEach(function(e){window.addEventListener(e,t,{passive:!0})})}();</script>


<span id="elementor-device-mode" class="elementor-screen-only"></span><iframe allow="join-ad-interest-group" data-tagging-id="AW-11381883891" data-load-time="1736902296276" height="0" width="0" src="https://td.doubleclick.net/td/rul/11381883891?random=1736902296269&amp;cv=11&amp;fst=1736902296269&amp;fmt=3&amp;bg=ffffff&amp;guid=ON&amp;async=1&amp;gtm=45Pe51e0v9171239473za200&amp;gcd=13l3l3l3l1l1&amp;dma=0&amp;tag_exp=101925629~102067555~102067808~102081485~102198178&amp;u_w=1920&amp;u_h=1080&amp;url=https%3A%2F%2Ftreinamentoonlinerdc.com.br%2Fplanilhas-personalizadas%2F&amp;hn=www.googleadservices.com&amp;frm=0&amp;tiba=PLANILHAS%20PERSONALIZADAS%20%E2%80%93%20Curso0nline&amp;npa=0&amp;pscdl=noapi&amp;auid=303689764.1736900473&amp;uaa=x86&amp;uab=64&amp;uafvl=Google%2520Chrome%3B131.0.6778.265%7CChromium%3B131.0.6778.265%7CNot_A%2520Brand%3B24.0.0.0&amp;uamb=0&amp;uam=&amp;uap=Windows&amp;uapv=19.0.0&amp;uaw=0&amp;fledge=1&amp;data=event%3Dgtag.config" style="display: none; visibility: hidden;"></iframe><iframe height="0" width="0" style="display: none; visibility: hidden;"></iframe><span id="elementor-device-mode" class="elementor-screen-only">
</span>
</body>
</html>
