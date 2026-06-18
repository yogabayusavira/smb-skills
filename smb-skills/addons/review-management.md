# review-management.md

## Purpose

Create a review management page that collects customer feedback and encourages satisfied customers to leave public reviews.

This page is typically accessed through:

* QR codes
* SMS follow-ups
* Email follow-ups
* Invoices
* Receipts
* Thank-you pages

This page should not be included in the main website navigation.

---

## Requirements

Required:

* Resend

This addon requires email delivery for customer feedback submissions.

Install Resend and configure the necessary environment variables before implementing the feedback form.

Resend need a domain.

---

## Page Structure

Hero

Rating Selection

Feedback Flow

Completion Message

---

## Hero

Purpose:

Ask the customer about their experience.

Example:

How was your experience with us?

Keep the page simple and focused.

---

## Rating Selection

Display a simple rating selector.

Example:

⭐ ⭐ ⭐ ⭐ ⭐

The rating selection should be the primary focus of the page.

---

## Feedback Flow

### Lower Ratings

If the customer selects a lower rating:

Redirect to an internal feedback form.

Purpose:

Collect customer feedback and identify service issues.

Form Fields:

* Name
* Email
* Feedback

Keep the form short.

Send submissions through Resend.

---

### Higher Ratings

If the customer selects a higher rating:

Redirect the customer to a public review platform.

Examples:

* Google Reviews
* Yelp
* Facebook Reviews

Use the review platform specified by the business.

---

## Completion Message

After feedback submission or review redirection, display a simple thank-you message.

Example:

Thank you for your feedback.

---

## Design Guidelines

Follow the design system defined in `smb-design.md`.

Keep the page focused on a single action.

Avoid unnecessary navigation and distractions.

---

## Completion

Confirm:

* Rating selection functions correctly.
* Lower ratings redirect to the feedback form.
* Feedback submissions are delivered through Resend.
* Higher ratings redirect correctly.
* The thank-you message displays correctly.
