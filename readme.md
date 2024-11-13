# dark:bg-gray-900 dark:text-white
# grid md:grid-cols-4 grid-cols-2

/* General page styling */
.main-wrapper {
  @apply bg-gray-50 flex items-center justify-center min-h-screen;
}

.containerl {
  max-width: 800px;
}

.btn {
  @apply inline-block bg-red-500 text-white py-2 px-4 rounded-lg transition duration-300;
}

.btn:hover {
  @apply bg-red-600;
}

/* Image styling */
.image-grid .image-box {
  @apply w-24 h-24 bg-gray-300 rounded-lg overflow-hidden;
}

.image-grid .image {
  @apply object-cover w-full h-full;
}

/* Vertical line styling */
.line {
  @apply w-px bg-gray-300;
}

@media (min-width: 768px) {
  /* Additional layout adjustments for larger screens */
  .line {
    left: 50%;
  }
}