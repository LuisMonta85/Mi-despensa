MI DESPENSA - primera versión

1. Abre index.html en Chrome, Edge o Samsung Internet.
2. Los datos se guardan en el navegador del dispositivo.
3. En Ajustes puedes exportar/importar copias JSON.
4. Añade/edita alimentos con sus valores nutricionales por 100 g, 100 ml o unidad.
5. Registra tickets manualmente o selecciona una foto. El OCR utiliza Tesseract.js desde CDN y puede necesitar conexión a Internet. La lectura es una ayuda: verifica siempre los datos.
6. Al confirmar una compra se suman cantidades a la despensa. En Consumo registra lo que se utiliza y se descontará del stock.

NOTAS DE ESTA VERSIÓN
- El guardado utiliza localStorage en esta primera entrega. Antes de instalarla como PWA o usar grandes volúmenes de datos, conviene migrar a IndexedDB.
- Los valores nutricionales de ejemplo son orientativos. Comprueba la etiqueta del producto y corrige su ficha.
- Los datos de compras, consumo y existencias son estimaciones domésticas; no equivalen a un registro nutricional clínico.
