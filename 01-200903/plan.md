Как компилировать в консоли: g++, clang++-10, ключ "-E", ключ "-I" (только один translation unit)

Как компилировать+линковать и отлаживать в CLion: можно создать проект и поехали. Можно положить рядом optimization.h

iostream, cin, cout

Показать UB (https://twitter.com/Nekrolm/status/1109797489576681472): неинициализированные переменные, выход за границу массива.
Показать, как запускать valgrind и компилировать с санитайзерами (сначала в консоли, потом в CLion): address, memory, undefined
Показать `-DGLIBCXX_DEBUG` и `#define GLIBCXX_DEBUG` (про препроцессор я не рассказывал, пока просто магические строчки)
Показать семантику копирования и что тормозит передачи в/из функций (чтобы можно было рассказывать про ссылки)