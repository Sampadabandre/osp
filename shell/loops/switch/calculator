#!/bin/bash

echo "Enter two numbers:"
read a b

echo "Choose operation:"
echo "1 = Addition"
echo "2 = Subtraction"
echo "3 = Multiplication"
echo "4 = Division"
read choice

case $choice in
  1)
    echo "Addition = $((a + b))"
    ;;
  2)
    echo "Subtraction = $((a - b))"
    ;;
  3)
    echo "Multiplication = $((a * b))"
    ;;
  4)
    if [ $b ne 0 ]; then
      echo "Division = $((a / b))"
    else
      echo "Error: Division by zero not allowed"
    fi
    ;;
  *)
    echo "Invalid choice"
    ;;
esac
