import 'dart:io';

void main() {
  String input = 'akc';
  try {
    int value = int.parse(input);
    print(value);
  } catch (error) {
    print(error);
  }
}
