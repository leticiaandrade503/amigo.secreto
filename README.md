* { box-sizing: border-box; }

body {
  font-family: Arial, sans-serif;
  background: #f4f1fb;
  color: #2d2640;
  margin: 0;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 16px;
}

main {
  background: #fff;
  width: 100%;
  max-width: 460px;
  padding: 28px;
  border-radius: 16px;
  box-shadow: 0 6px 24px rgba(60, 40, 120, .15);
}

h1 { margin-top: 0; text-align: center; }

.linha { display: flex; gap: 8px; }

input {
  flex: 1;
  padding: 10px 12px;
  border: 2px solid #cfc6ee;
  border-radius: 8px;
  font-size: 1rem;
}

button {
  padding: 10px 16px;
  border: none;
  border-radius: 8px;
  background: #6c4fd6;
  color: #fff;
  font-size: 1rem;
  cursor: pointer;
}
button:hover { background: #5a3fc0; }

button.sortear { width: 100%; margin-top: 16px; background: #1f9d6b; }
button.sortear:hover { background: #178358; }

ul { padding-left: 20px; min-height: 24px; }

#resultado {
  font-weight: bold;
  text-align: center;
  font-size: 1.2rem;
  min-height: 28px;
}

#reiniciar { display: block; text-align: center; margin-top: 12px; color: #6c4fd6; }
