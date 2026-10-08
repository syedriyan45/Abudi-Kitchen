ABUDI Kitchen correct Firebase fix.
The Firestore startup calls are inside the same IIFE as loadOrders().
The duplicate previousOrderIds declaration was removed.
