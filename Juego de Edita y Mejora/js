const express = require('express');
const app = express();
const port = 3000;

app.use(express.json());
app.use(express.static('public'));

app.post('/submit-edit', (req, res) => {
    const userEdit = req.body.edit;
    // Procesa y compara la edición con el texto original
    // Responde con retroalimentación
    res.json({ feedback: "Retroalimentación generada..." });
});

app.listen(port, () => {
    console.log(`Servidor corriendo en http://localhost:${port}`);
});
