updated_book.delete()

books = Book.objects.all()

print(list(books))
