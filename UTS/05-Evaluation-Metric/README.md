# \# Rencana Evaluation Metric

# 

# Perbandingan Prithvi-EO-2.0 (model utama) vs U-Net ResNet-50 (pembanding)

# untuk klasifikasi tutupan hutan TNBTS dari citra Sentinel-2.

# 

# | Metrik | Kegunaan |

# |---|---|

# | Overall Accuracy (OA) | Akurasi keseluruhan piksel |

# | Precision, Recall, F1-score (per kelas) | Kinerja tiap kelas, penting jika kelas tidak seimbang |

# | IoU / mIoU | Metrik utama segmentasi, mengukur overlap prediksi dengan label |

# | Cohen's Kappa | Standar evaluasi klasifikasi tutupan lahan di penginderaan jauh |

# | Confusion Matrix | Melihat kelas mana yang sering tertukar |

# 

# Skenario data terbatas: kedua model diuji pada 10%, 25%, 50%, dan 100% data latih

# untuk melihat model mana yang lebih stabil saat data sedikit.

