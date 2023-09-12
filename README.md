```javascript
// Definir o cronograma da manhã
const cronogramaManha = [
  { horario: '08:00 - 09:30', atividade: 'Aula de Matemática' },
  { horario: '09:45 - 11:15', atividade: 'Aula de Ciências' },
  { horario: '11:30 - 12:00', atividade: 'Recreio' }
];

// Definir o cronograma da tarde
const cronogramaTarde = [
  { horario: '13:30 - 15:00', atividade: 'Estudos de História' },
  { horario: '15:15 - 16:45', atividade: 'Estudos de Inglês' }
];

// Exibir o cronograma da manhã
console.log('Cronograma da Manhã:');
for (const atividade of cronogramaManha) {
  console.log(`${atividade.horario}: ${atividade.atividade}`);
}

// Exibir o cronograma da tarde
console.log('\nCronograma da Tarde:');
for (const atividade of cronogramaTarde) {
  console.log(`${atividade.horario}: ${atividade.atividade}`);
}
