# Few-Shot Classification: YandexGPT Test

## 🎯 Goal
Testing the impact of Few-Shot prompting on classification accuracy using YandexGPT API.

## 🧪 The Task
Classify customer requests into categories (Refund, Delivery Status, Tech Issue, Order Cancellation).

## 📊 Results
We compared **Zero-Shot** (just a question) vs **Few-Shot** (with examples).

| Method | Result | Observation |
| :--- | :--- | :--- |
| **Zero-Shot** | ❌ Often wrong | Model guesses without context. |
| **Few-Shot** | ✅ **Correct** | Model learned the pattern from 3 examples. |

**Test Case:** "Cancel order #987"
**Model Output:** `Категория: Отмена заказа` (Correct)

## 📎 Conclusion
Few-Shot prompting significantly improves accuracy for classification tasks by providing reasoning patterns.
