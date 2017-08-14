---

---

# View / Amend / Cancel

Whether the customer intends to cancel or amend the booking, we recommend you always perform a view request first. That way you will be able to present the user with all relevant information about the booking.

| View booking | [https://api.holidayextras.co.uk/v1/booking/foo](view) | GET |
| Amend booking - Parking | [https://api.holidayextras.co.uk/v1/booking/foo](amend) | GET & POST |
| Amend booking - Hotels | [https://api.holidayextras.co.uk/v1/booking/foo](amendhotels) | GET & POST |
| Amend booking (Parking and Hotels) - Personal Details only - no reprice | [https://api.holidayextras.co.uk/v1/booking/foo](amendnoreprice) | GET & POST |
| Cancel booking | [https://api.holidayextras.co.uk/v1/booking/foo](cancel) | GET & POST |