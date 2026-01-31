SELECT DISTINCT ?film ?filmLabel ?capital_cost
WHERE {
  ?film wdt:P31 wd:Q202866 ;  # Экземпляры мультфильмов (Q202866)
        wdt:P136 ?genre ;     # Жанр мультфильма (обязательно)
        wdt:P495 ?country ;   # Страна происхождения (обязательно)
        wdt:P2047 ?duration;  # Продолжительность (в минутах, обязательно)
        wdt:P2130 ?capital_cost. # Затраты на мультфильм (budget)

  SERVICE wikibase:label { bd:serviceParam wikibase:language "ru" }
}
