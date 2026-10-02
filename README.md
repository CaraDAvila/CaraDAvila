<img width="880" height="369" alt="50deb56e0857599e89871089c3d6cf33-ezgif com-effects" src="https://github.com/user-attachments/assets/c5e03dc9-ecc3-456a-8efc-49877e4aee60" />

<img width="2000" height="2000" alt="octocat-git" src="https://github.com/user-attachments/assets/cf08e0ad-4300-4f21-b29f-6549b7b7473d" />


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>README layout</title>
<style>

.header{display:flex;justify-content:space-between;align-items:center;color:var(--muted);font-size:14px}
.header strong{color:var(--text)}


.banner{height:160px;padding:0;position:relative;overflow:hidden;
background:
repeating-linear-gradient(90deg,transparent 0 22px,rgba(31,59,255,.35) 22px 26px),
linear-gradient(180deg,rgba(31,59,255,.35),transparent 70%),#05070d}

/* 3. main two-column area */
.main{display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1.5fr);gap:12px}
.side{min-height:360px;background:var(--panel)}
.content{display:grid;gap:12px;align-content:start}
.text{padding:20px;background:var(--panel)}
.text p{margin:0;max-width:62ch}
.extra{min-height:140px;width:70%;background:var(--panel)}

@media (max-width:720px){
.main{grid-template-columns:1fr}
.side{min-height:220px}
.extra{width:100%}
}
</style>
</head>
<body>
<main class="page">
  <header class="box header"><span>username / <strong>README</strong>.md</span><span aria-hidden="true">✎</span></header>

  <section class="box banner" aria-label="Banner"></section>

  <div class="box main">
    <aside class="box side" aria-label="Sidebar / image"></aside>
    <div class="content">
      <section class="box text">
        <p><strong>LOREM IPSUM</strong> dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </section>
      <section class="box extra" aria-label="Secondary block"></section>
    </div>
  </div>
</main>
</body>
</html>
