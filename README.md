<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Everton Patinetes</title>

<style>
*{box-sizing:border-box;margin:0;padding:0;font-family:Arial,sans-serif}
body{background:#f3f6f5;color:#173b32}
.app{max-width:430px;margin:auto;min-height:100vh;background:white;padding-bottom:75px}

header{background:#0d5c48;color:white;padding:28px 20px;border-radius:0 0 24px 24px}
header h1{font-size:24px;margin-bottom:6px}
header p{font-size:14px;opacity:.9}

.card{margin:18px;padding:20px;background:#e8f4ef;border-radius:18px}
.card small{color:#55736a}
.card h2{font-size:28px;margin:8px 0 15px}

button{border:0;background:#0d5c48;color:white;padding:12px 18px;border-radius:12px;font-weight:bold;cursor:pointer}

.resumo{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin:18px}
.box{padding:16px;background:#f3f6f5;border-radius:15px}
.box small{color:#71827d}
.box strong{display:block;margin-top:7px;font-size:18px}

.tela{display:none;padding:18px}
.tela.ativa{display:block}

.patinete{border:1px solid #e1e8e5;border-radius:18px;padding:14px;margin-bottom:15px}
.patinete img{width:100%;height:170px;object-fit:cover;border-radius:14px}
.patinete h3{margin:12px 0 6px}
.patinete p{color:#65746f;font-size:14px;margin-bottom:10px}

.linha{display:flex;justify-content:space-between;margin:10px 0}

.oferta{background:#fff4d8;padding:18px;border-radius:18px;margin-bottom:15px}
.oferta h3{margin-bottom:8px}

.voltar{background:#555;margin-top:15px}

nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);
width:min(430px,100%);background:white;border-top:1px solid #ddd;
display:flex;justify-content:space-around;padding
