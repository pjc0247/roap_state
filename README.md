roap_state
====

```rb
class Player
  attr_accessor :level

  #--if @level<=5
  def DODIE
    puts "당신으 죽엇읍니다. 아무런 패널티 업이 부활함니다."
  end
  
  #--if @level>5
  def DODIE
    puts "죽업습이다, 999999의경험치를일습니다"
  end
end

p = Player.new

p.level = 1
p.DODIE

p.level = 6
p.DODIE
```
