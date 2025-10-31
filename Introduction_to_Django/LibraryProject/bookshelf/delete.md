
---

### **`delete.md`**
```markdown
### DELETE Operation

**Command:**
```python
book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()

# Confirm deletion
Book.objects.all()
