unless ENV['DISABLE_DANGER_RUBOCOP']
  rubocop.lint(
    force_exclusion: true,
    inline_comment: true,
    report_danger: true,
  )
end

unless ENV['DISABLE_DANGER_SUGGESTER']
  suggester.suggest
end
