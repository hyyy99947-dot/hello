# hello
#include &lt;iostream> #include &lt;fstream> using namespace std;  int main() {     fstream file;     file.open("hello.txt", ios::in|ios::out);      file &lt;&lt; "hello?\n";     file.close();       return 0; }
