cv2.imshow('Original', img)  # Orijinal görüntü
cv2.imshow('Gray', gray)  # Grayscale görüntü
cv2.imshow('Binary', binary)  # Binary görüntü
cv2.imshow('Inverted', inverted)  # Ters çevrilmiş görüntü
cv2.imshow('Flood-Filled', filled_image)  # Çukurlar doldurulmuş görüntü
cv2.imshow('Eroded', eroded)  # Aşındırılmış görüntü
cv2.waitKey(0)
cv2.destroyAllWindows()
