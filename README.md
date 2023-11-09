# List Methods in Python

- [Introduction](#introduction)
- [list.append(x)](#list.append(x))
- [list.extend(iterable)](#extend)
- [list.insert(i, x)](#insert)
- [list.remove(x)](#remove)
- [list.pop([i])](#pop)
- [list.clear()](#clear)
- [list.index(x[, start[, end]])](#index)
- [list.count(x)](#count)
- [list.sort(key=None, reverse=False)](#sort)
- [list.reverse()](#reverse)
- [list.copy()](#list.copy())

## Introduction
The list data type in Python comes with several built-in methods. Here's an overview of these methods:

## list.append(x)
Add an item to the end of the list. Equivalent to `a[len(a):] = [x]`.

## list.extend(iterable)
Extend the list by appending all the items from the iterable. Equivalent to `a[len(a):] = iterable`.

## list.insert(i, x)
Insert an item at a given position. The first argument is the index of the element before which to insert.

## list.remove(x)
Remove the first item from the list whose value is equal to x. Raises a ValueError if there is no such item.

## list.pop([i])
Remove the item at the given position in the list and return it. If no index is specified, removes and returns the last item.

## list.clear()
Remove all items from the list. Equivalent to `del a[:]`.

## list.index(x[, start[, end]])
Return the zero-based index in the list of the first item whose value is equal to x. Raises a ValueError if there is no such item.

## list.count(x)
Return the number of times x appears in the list.

## list.sort(key=None, reverse=False)
Sort the items of the list in place.

## list.reverse()
Reverse the elements of the list in place.

## list.copy()
Return a shallow copy of the list. Equivalent to `a[:]`.


