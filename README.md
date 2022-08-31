# Dart-const-final-properties-function
Dart-const/final properties function
void main()
{
  const FOOO obj=const FOOO();}
class FOO
{
  late final int c;
  late final int a;//it should be intialize at compile time
  static const int b=2;//it must have value at run time
}

class FOOO//everything is const
{
  
  final int a=12;//it should be intialize at compile time
  final int b=2;//it must have value at run time
  const FOOO();//const constructor  has no body
  
}

