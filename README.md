# Project
Artificial Intelligence Algorithms Seminar talks about Recurrent Neural Networks
The idea behind RNNs is to make use of continuous information and while referring to the previous inputs unlike NN which refers to the inputs in an independent way i.e. in a traditional neural network (NN) we assume that all inputs (and outputs) are independent of each other. So for many tasks it's a bad idea. If we want to predict the next word in the sentence, you should know which words came before it.

  RNNs are called recurrent because they perform the same task for each element in a sequence, with the output depending on the previous computations. Another way to think about RNNs is that they have a "memory" which captures information about what has been thought so far.

The advantage of convolution layers is the utilization of the spatial relationship between different elements in the data, such as pixels in an image. There are data types in which the various members form a series in which the order of the members is important, such as text, sound waves, DNA sequence and more. Of course, this type of data requires a model that gives importance to the order of the members, which is not present in convolutional networks. In addition, many times the dimension of the input is unknown or changes, such as the number of words in a sentence, and this must also be taken into account. To deal with these challenges, an architecture must be built that receives a series of vectors and outputs a single vector, where the single vector encodes relationships on the original data that entered it. The output vector can be transferred in the FC layer or in any other classifier, depending on the nature of the task.
סמינר אלגוריתמים של בינה מלאכותית מדבר על רשתות עצביות חוזרות.
הרעיון מאחורי RNNs הוא לעשות שימוש במידע רציף ותוך כדי התייחסות לכניסות הקודמות בניגוד ל-NN שמתייחס לכניסות בצורה עצמאית כלומר ברשת עצבית מסורתית (NN) אנו מניחים שכל הכניסות (והיציאות) אינן תלויות ב אחד את השני. אז עבור משימות רבות זה רעיון רע. אם נרצה לחזות את המילה הבאה במשפט, כדאי לדעת אילו מילים הגיעו לפניה.

   RNNs נקראים חוזרים מכיוון שהם מבצעים את אותה משימה עבור כל אלמנט ברצף, כשהפלט תלוי בחישובים הקודמים. דרך נוספת לחשוב על RNNs היא שיש להם "זיכרון" אשר לוכד מידע על מה שחשבו עד כה.

היתרון של שכבות קונבולציה הוא ניצול הקשר המרחבי בין אלמנטים שונים בנתונים, כמו פיקסלים בתמונה. ישנם סוגי נתונים בהם האיברים השונים יוצרים סדרה בה יש חשיבות לסדר האיברים כמו טקסט, גלי קול, רצף DNA ועוד. כמובן שסוג זה של נתונים מצריך מודל שנותן חשיבות לסדר החברים, שאינו קיים ברשתות קונבולוציוניות. בנוסף, פעמים רבות מימד הקלט אינו ידוע או משתנה, כמו מספר המילים במשפט, ויש לקחת זאת גם בחשבון. כדי להתמודד עם אתגרים אלו, יש לבנות ארכיטקטורה שמקבלת סדרה של וקטורים ומוציאה וקטור בודד, כאשר הווקטור הבודד מקודד קשרים על הנתונים המקוריים שנכנסו אליו. ניתן להעביר את וקטור הפלט בשכבת FC או בכל מסווג אחר, בהתאם לאופי המשימה.