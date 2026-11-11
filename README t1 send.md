import 'dart:io';

void main() {
  print('Enter your birth year:');
  int birthYear = int.parse(stdin.readLineSync()!);

  int currentYear = 2026;
  int age = currentYear - birthYear;

  print('Your age is: $age');
}
