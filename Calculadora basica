import 'dart:io';

void main() {
  print('Calculadora Básica');
  print('Escolha uma operação:');
  print('1. Adição');
  print('2. Subtração');
  print('3. Multiplicação');
  print('4. Divisão');

  // Leitura da operação escolhida
  String? choice = stdin.readLineSync();
  
  // Leitura dos números
  print('Digite o primeiro número:');
  double num1 = double.parse(stdin.readLineSync()!);

  print('Digite o segundo número:');
  double num2 = double.parse(stdin.readLineSync()!);

  // Realiza a operação escolhida
  switch (choice) {
    case '1':
      print('Resultado: ${num1 + num2}');
      break;
    case '2':
      print('Resultado: ${num1 - num2}');
      break;
    case '3':
      print('Resultado: ${num1 * num2}');
      break;
    case '4':
      if (num2 != 0) {
        print('Resultado: ${num1 / num2}');
      } else {
        print('Erro: Divisão por zero');
      }
      break;
    default:
      print('Opção inválida');
      break;
  }
}
