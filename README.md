# dart_hands_on

2022 Flutter Festival: GDG Daejeon

![session card image](./session-card.png)

## μΈμ κ°μ

### π© Flutter μλ¬Έμλ₯Ό λμμΌλ‘ μ§νλλ λ€νΈ μΈμ΄ νΈμ¦μ¨ μΈμμλλ€.

λ€νΈλ ν΄λμ€ κΈ°λ°μ κ°μ²΄ μ§ν₯ μ»΄νμΌ μΈμ΄μλλ€. λ€νΈμ λ¬Έλ² μ€νμΌμ C μΈμ΄μ κ±°μ μ μ¬νλ©° Java, C#, JavaScript μμμ κΈ°λ₯μ  μ€νΈλ­μ³λ₯Ό μΆκ°ν΄ λ³΄λ€ κ°κ²°νκ³  κ°λ ₯ν κΈ°λ₯μ μ§μνκ³ μμ΄, κ΄λ ¨ μΈμ΄ κ²½νμ΄ μμΌμ  λΆλ€μ λμ± μΉμνκ² μ ν΄λ³΄μ€ μ μμ΅λλ€.

### π© μ€λμ ν  μΌμ μΆκ°νκ³  μμ , μ­μ νλ ν¬λ νλ‘κ·Έλ¨μ μμ±ν΄λ³΄λ©΄μ νλ¬ν°λ₯Ό κ΅¬ννκΈ° μν΄ μμμΌν  λ€νΈμ ν΅μ¬ λ¬Έλ² κΈ°λ³ΈκΈ°λ₯Ό λΉ λ₯΄κ² νμ΅νκ³  νμ©ν΄λ΄λλ€.

- νμ λ³ λ³μ, μμ μ μΈκ³Ό μ»¨λ²€μ
- ν΄λμ€ μμ±κ³Ό μ¬μ©
- ν¨μ μμ±κ³Ό νΈμΆ
- μ΄κ±°ν `enum` κ³Ό `extension method` νμ©
- κ³ μ°¨ν¨μ `map()`, `where()`, `toList()`
- control flow `if`, `switch`
- Type Casting

## μΈμ νκ²½ κ΅¬μ±

### π νλ¬ν° νκ²½ κ΅¬μ±μ΄ μλ£λ μνλΌλ©΄

```shell
$ git clone https://github.com/macaronpark/dart-hands-on.git
```

`dart-hands-on/lib/dart_hands_on.dart` μμ μ½λλ₯Ό ν¨κ» μμ±ν©λλ€.
flutter run with chrome μΌλ‘ λΈλΌμ°μ  μ½μμμ νλ‘κ·Έλ¨ μνλ₯Ό νμΈνλ©° μ§νλ©λλ€.

### π νλ¬ν° νκ²½ κ΅¬μ±μ΄ λμ΄μμ§ μμ μνλΌλ©΄

https://dart.dev/#try-dart λ‘ μ μν΄ λ³λμ νκ²½ κ΅¬μ±μμ΄ λΈλΌμ°μ μμ μλ μ½λλ₯Ό λΆμ¬λ£κΈ°νμ¬ μ§ννμ€ μ μμ΅λλ€.

```Dart
// π `Todo` class
//
// tip 1. λ©€λ² λ³μ: κ³ μ  μμ΄λ, ν  μΌ μ λͺ©, μλ£ μ¬λΆ, μμ± μΌμ
// tip 2. `late` modifier
// tip 3. μμ `final` vs. `const`
// tip 4. ν΄λμ€ μμ±μ with syntactic sugar

// π `FieldNames` enum
//
// tip 1. enum { μΌμ΄μ€, μΌμ΄μ€, }

// π `FieldNamesExtension` extension
//
// tip 1. extention μ΅μ€νμλͺ on λμ {}

void main() {
  // GDG Daejeon Flutter Festival
  // Session 1. <μ΄ μΈμμ λ£κ³  5λΆλ§μ νλ¬ν° μ±μ λ§λ€μμ΅λλ€: λ€νΈ μΈμ΄ κΈ°λ³ΈκΈ°> - suzy
  //
  //
  // π¦ λͺ©ν: μ€λμ ν  μΌμ μΆκ°νκ³  μμ , μ­μ νλ νλ‘κ·Έλ¨μ μμ±ν©λλ€.

  // π ν¬λ λͺ©λ‘μ μ μ₯ν  λ°°μ΄μ΄ νμν©λλ€.
  //
  // tip 1. λ³μ `var` vs. `type annotation`
  // tip 2. `List` class
  // tip 3. https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo#avoid-using-var-and-dynamic

  // π μ€λμ ν  μΌμ μΆκ°νλ €κ³  ν©λλ€. λ¨Όμ  ν¬λ ν΄λμ€λ₯Ό λ§λ€μ΄μ£ΌμΈμ.

  // π λ κ°μ μ ν¬λλ₯Ό λ§λ€μ΄μ£ΌμΈμ.
  //
  // - id: 1, title: "λ€νΈ νΈμ¦μ¨ μΈμ λ£κΈ°"
  // - id: 2, title: "νλ¬ν° νΈμ¦μ¨ μΈμ λ£κΈ°"

  // π μλ‘μ΄ ν¬λλ₯Ό κΈ°μ‘΄μ ν¬λ λͺ©λ‘μ μΆκ°νλ ν¨μ `addTodos(:newTodos)` λ₯Ό μμ±ν΄μ£ΌμΈμ.
  //
  // tip 1. λ°νκ° ν¨μλͺ(μΈμ) {}
  // tip 2. Named parameters

  // π `addTodo(:newTodo)` λ₯Ό μ¬μ©νμ¬ ν¬λλ₯Ό λͺ©λ‘μ μΆκ°ν΄μ£ΌμΈμ.

  // π ν¬λ λͺ©λ‘ λ΄ νΉμ  ν¬λμ μ λ³΄λ₯Ό μμ νλ ν¨μ
  //    `updateTodo(:id :fieldName :newValue)` λ₯Ό μμ±ν΄μ£ΌμΈμ.
  //
  // tip 1. μΈμ fieldName μ Enumerated types `FieldNames` λ₯Ό μ¬μ©ν΄ ν΄λ¨Όμλ¬λ₯Ό λ°©μ§ν΄μ£ΌμΈμ.
  // tip 2. μΈμ newValue μ νμμ String λλ bool μ΄μ΄μΌ ν©λλ€.
  // tip 3. `dynamic` vs `Object`
  // tip 4. type casting

  // π `updateTodo(:id :fieldName :newValue)` λ₯Ό μ¬μ©νμ¬
  //    κ³ μ  μμ΄λ 1λ² ν¬λμ μ λͺ©μ "new title!" λ‘ λ³κ²½ν΄μ£ΌμΈμ.

  // π ν¬λ λͺ©λ‘ λ΄ νΉμ  ν¬λλ₯Ό μ­μ νλ ν¨μ `deleteTodo(:id)` λ₯Ό μμ±ν΄μ£ΌμΈμ.
  //
  // tip 1. where, toList

  // π `deleteTodo(:id)` λ₯Ό μ¬μ©νμ¬ κ³ μ  μμ΄λ 1λ² ν¬λλ₯Ό μ­μ ν΄μ£ΌμΈμ.

}
```

## μ°Έκ³ 

- [flutter.dev: Install Flutter](https://docs.flutter.dev/get-started/install)
- [dart.dev: Language Tour](https://dart.dev/guides/language/language-tour)
