Пример "нарушения" правила пяти (когда деструктор на самом деле не нужен): list_heap.

Главное правило в C++: правило нуля.
   Если можно, то не надо реализовывать ни одно из: деструктор, конструктор копий/перемещения, operator=.
   Как добиться: не управлять ничем руками, использовать vector/shared_ptr/unique_ptr.