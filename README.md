# PolygonOrientation
التوجه للمضلع / Polygon Orientation / Orientation du polygone
***********************************************************************************************************************************
المعطيات : المضلع | النتيجة : قطعة مستقيمة تمثل الاتجاه
نبحث أولا عن أقصى المسافتين بين رؤوس الشكل (ن ن) ثم نتحصل عن الاتجاه بحساب متوسط القطعتين
***********************************************************************************************************************************
Input : The polygon | Output : a line segment
Firstly search the 2 max distances between all vertices of the polygon (n x n) then the average between the two segments gives the orientaion
***********************************************************************************************************************************
Entrée:Le polygon  |   Sortie:un segment[p,pp] representant l'orientaion
recherche tout d'abord les 2 plus grandes distances entre tous les sommets entre eux (n x n)
ensuite la moyenne de ces deux segments est le segment d'orientation
